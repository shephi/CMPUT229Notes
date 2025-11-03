```c
aswap(int, int*)

while (aswap(1, &1)) {}
//aswap returns 1 if it failed to swap or returns the value that was at the memory address if successful in swapping!
```

```arm-asm
# Processor P0: s1: address of shared, s4: local value to be swapped
# Processor P1: s1: address of shared, s4: local value to be swapped

# P0, P1: Let s1 <- 0x1000 10E0
# P0: s4: 42, t0, 42, t1: 0
# P1: s4: 15, t0, 15, t1 :0

try:
	lr.w t0, (s1) # load reserved 
	# have as litte instructions between these two instructions
	sc.w t1, s4, (s1) # store conditional
	bne t1, zero, try # branch if store fails
	add s4, zero, t0 # put loaded value in s4
```

- Load reserved: lr.w rd, (rs1) (Holds 1 load reserved address at a time)
- Store conditional: sc.w rd, rs2, (rs1)
	- Succeeds if location has not changed since lr.w
		- Returns zero in rd
	- Fails if location has changed 
		- Returns non-zero