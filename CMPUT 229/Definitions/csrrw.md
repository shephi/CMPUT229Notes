
csrrw t0, 0, t1
0 # Specifies the CSR where to perform operation
	CSR0 # [[ustatus]]
t0 <- CSR0 zero extended
CSR0 <- t1

