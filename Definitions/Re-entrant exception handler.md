
``` armasm
# ---- This code causes a segmentation fault ----
li sp, 0
lw t0, 0(sp)
# ---- This coded causes an unaligned access exception ----
li sp, 0x80008001
lw t0, 0(sp)
```

sp is corrupted -> cant save registers in the user stack -> must create stack in the kernel area

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
csrrw t0, 0x040 
```

