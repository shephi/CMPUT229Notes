Function: 
- Eliminate artificial data hazards that limit the instruction-level parallelism achievable in the CPU pipeline
- Register renaming ensures that when an instruction is issued to execute out of order, it does not incorrectly use a stale value or overwrite a value needed by an unrelated instruction
Implementation:
- Reservation Stations: 
	- When an instruction is issued (in-order), it is sent to a reservation station (Renaming process occurs here)
		- If the instructions required operand is **already available** in the **register file** or the **reorder buffer,** that value is copied directly to the **reservation station**
		- If the operand is **not yet available** (because a prior instruction hasn't finished calculating it), the reservation station records which **functional unit** will produce the result, so it can receive the data directly when it is computed (bypassing the architectural register file write
		- **Reorder Buffer:** This unit buffers the results of instructions that have executed out of order. It is essential because, despite the out-of-order execution, results must **commit (write back to the architectural registers) in the original program order** to maintain precise state