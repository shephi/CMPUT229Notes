
``` arm-asm
# ---- This code causes a segmentation fault ----
li sp, 0
lw t0, 0(sp)
# ---- This coded causes an unaligned access exception ----
li sp, 0x80008001
lw t0, 0(sp)
```

1. sp is corrupted 
2. cant save registers in the user stack
3. must create stack in the kernel area

[[uscratch]]

``` arm-asm
.data
iTrapData: .space 4000

.text
atStartUp:
csrrw t0, 0x040, t0 # t0 <- uscratch; uscratch <- 10
la t0, kstack # 
addi t0, t0, 4000 # kstack is the lowest address of allocated range
csrrw t0, 0x040, t0 # t0 <- t0 original value
<other initialization tasks>

handler:
csrrw t0, 0x040, t0 # t0 <- ksp; uscratch <- 10
sw t1, -4(t0) # Mem[ksp-4] <- t1
addi t1, t0, -16 # t1 <- updated ksp
csrrw t0, 0x040, t1 # t0 <- t0 original value;
					# uscratch <- updated ksp;
					
<enable exceptions because uscratch contains the correct ksp>
sw t0, 8(t1) # save t0 into kstack
sw t2, 4(t1) # save t2 into kstack
sw t3, 0(t1) # save t3 into kstack
<handler can use t0, t2, t3>
...
lw t0, 8(t1) # restore t3 from kstack
lw t2, 4(t1) # restore t2 from kstack
lw t3, 0(t1) # restore t3 from kstack
lw t1, 12(t1) # restore t1 from kstack
<disable exceptions while updating ksp in sscratch>
csrrw t0, 0x040, t0 # t0 <- ksp; uscratch <- 10
addi t0, t0, 16 # t0
csrrw t0, 0x040, t0
<enable exceptions and return>

```
