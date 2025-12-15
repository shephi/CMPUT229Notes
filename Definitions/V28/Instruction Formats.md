- R-Type Instruction (Register-to-Register Instruction):
	- 4 steps:
		1. **Fetch instruction** from instruction memory and increment PC
		2. **Read two registers** (I19-I15) and (I25-I20) from the register file; also the main control unit computers the setting of the control lines during this step
		3. The **ALU operates** on the data read from the register file, using portions of the opcode to generate the ALU function
		4. Write the **ALU result** to the destination register (I11-I7)
		5. ![[image-4.png]]
- I-Type Instruction (Load Instruction):
	- 5 steps:
		1. **Fetch instruction** from instruction memory and increment PC
		2. **Read one register** (I19-I15) from the register file
		3. The **ALU computes** the sum of the value read from the register file and the sign extended 12 bits of the instruction **(offset)**
		4. Use the result of the ALU as the **address for the data memory**
		5. Write the data from the memory unit to the destination register (I11-I7)
		6. ![[image-5.png]]
- S-Type Instruction (Store Instruction):
	- ![[image-6.png]]
- SB-Type Instruction (Branch Instruction):
	- 4 Steps:
		1. **Fetch instruction** from instruction memory and increment PC
		2. **Read two registers** I19-I15 and (I24-I20) from the register file
		3. The **ALU subtracts** one data value from the other data value, both read from the register file. The value of PC is added to the sign-extended, 12 bits of the instruction **(offset)** left shifted by one; the **result is the branch target address**
		4. The **zero status** information from the ALU is used to decide which adder result to store in the PC
		5. ![[image-7.png]]
