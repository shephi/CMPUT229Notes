- What should the processor do when an exception occurs?
	1. Save the address of the instruction that caused the exception
		- Where?
			- In a special register called the User Exception Program Counter (uepc)
	2. Jump to a specified address (Address stored in the User Trap Handler Base Adress (utvec) register)
		- This is the first instruction of the exception handler
		- what code should be there?
			- OS code to handle exceptions
	3. OS either:
		- Terminates the process that caused the exception
		- Takes care of the exception condition and restarts the process
- Exception Handler:
	- Examines the cause of the exception
	- Jumps to the OS handler of that exception
