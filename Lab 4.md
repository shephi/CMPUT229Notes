CLINT -> Core-Local Interrupter
	Defines a few MMIO locations that is agreed upon in the RISC-V community
		Ex. TIME, TIMECMP, etc.
	Gives timer functionality to RISC-V and their associated "HARTS"
- How do timer interrupts work?
	- Outside the HART CLINT works hard comparing TIMECMP to TIME (TIME >= TIMECMP) whenever this occurs a interrupt is sent to the associated HART
- How do we use timer interrupts?
	- Say we want a interrupt in 1/2 a second (600 milliseconds). We need to set TIMECMP to the time we want the interrupt to occur
	- TIMECMP = TIME + 500
	- Therefore as time continues ticking eventually time will be larger or equal to TIMECMP -> Interrupt
- Ex. 
	- Say 2 seconds have passed since the start of the program (TIME = 2000)
	- We want an interrupt to occur in 1/2 a second