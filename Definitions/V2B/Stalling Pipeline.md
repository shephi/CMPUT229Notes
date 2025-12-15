When a load/use bubble is needed?
- Rs1 = Rd or Rs2 = Rd
- If MemRead = 1

How to stall pipeline
- Force all control lines in ID/EX to 0:
	- EX, MEM WB, will execute nop (no operation)
	- Repeating decoding of instruction in ID
	- Change PC to fetch the instruction in IF again