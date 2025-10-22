jump: unconditional jump to an address
	jump target # jumps to target
jal: unconditional jump to a known offset + save return address
	jal t1, target # t1 <- return address, jump to target
jalr: unconditional jump to an address held in a register + save return address
	jalr t1, a0, 0  # t1 <- return address, jump to a0 + immediate value (0)
