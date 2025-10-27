```c
while (save[i] == k)
	i = i + j;
	...
```

1. `load [save[i]]
2. `save[i] != k?
	- Done Loop
3. `Loop: i <- i + j
4. `load save[i]
5. `save[i] = k?
	- Loop
6. Done Loop

```arm-asm
	  slli t1, t3, 2 # t1 <- i * 4
	  add t1, t1, s6 # t1 Addr(save[i])
	  lw t0, 0(t1) # t0 <- savi[i]
	  bne t0, s5, DoneLoop # if save[i] != k goto 
Loop: add s3, s3, s4 # i <- i + j
	  slli t1, s3, 2 # t1 <- i * 4
	  add t1, t1, s6 # t1 <- Addr(save[i])
	  lw t0, 0(t1) # t0 <- save[i]
	  beq t0, s5, Loop # if save[i] != k goto
DoneLoop:
```