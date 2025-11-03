```c
void clear1(int array[], int size){
	int i;
	for (int i = 0; i < size; i += 1)
		array[i] = 0;
}
```

*add, addi, slli: 1 cycle, sw: 5 cycles; blt, ble: 2 cycles

```arm-asm
	   ble a1, zero, done # if n <- 0
	   mv t0, zero        # i <- 0 
loop1: slli t1, t0, 2     # t1 <- i * 4
	   add t2, a0, t1     # t2 <- &array[i]
	   sw zero, 0(t2)     # array[i] <- 0 
	   addi t0, t0, 1     # i <- i + 1
 	   blt t0, a1, loop1  # if i < size goto loop1
# Num of instructions  = 5 * size + 2
# Num of cycles = 1 + 2 + size * (1+1+5+1+2)
#               = 10 * size + 3
# CPI = Num of Cycles / Num of Instructions
# CPI = (10 * size + 3) / (5 * size + 2) = 2

```


```c
void clear2(int *array, int size){
	int *p;
	for (p = &array[0]; p < &array[size]; p += 1)
		*p = 0;
}
```

```arm-asm
	  ble a1, zero done # if n <- 0
	  mv t0, a0         # p <- &array[0]
	  slli t1, a1, 2    # t1 <- size * 4
	  add t2, a0, t1    # t2 <- &array[size]
loop2:sw zero, 0(t0)    # M[p] <- 0
      addi t0, t0, 4    # p <- p + 4
      blt t0, t2, loop2 # if p<&array[size] goto loop2
# Num of instructions = 3 * size + 4
# Num of Cycles = 5 + size * (5 + 1 + 2)
#               = 8 * size + 5
# CPI = Num of Cycles / Num of Instructions
# CPI = (8 * size + 5) / (3 * size + 4) = 2.67  
```

```
# of cycles (index) = 10 * size + 3
# of cycles (ptr)   = 8 * size + 5 
# Speedup             = Performance (index) / Performance (ptr) 
# Speedup             = (10 * size + 3) / (8 * size + 5) = 1.25
# index is 1.25 times faster than pointer  
```
