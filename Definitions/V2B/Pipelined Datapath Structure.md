The pipelined datapath divides instruction execution into five standard stages, separated by **pipeline registers** (IF/ID, ID/EX, EX/MEM, MEM/WB). These registers are essential to hold the information produced in a preceding clock cycle for use in the subsequent cycle

**Instruction Fetch (IF):** Fetches the instruction from instruction memory.

**Instruction Decode (ID):** Reads operands from the Register File.

**Execute (EX):** Performs the ALU operation or address
calculation.

**Memory Access (MEM):** Accesses data memory (read/write).

**Write Back (WB):** Writes the final result back to the registers.