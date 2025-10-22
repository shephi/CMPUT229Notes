## Practice Material
- [[Introduction (Quiz 0)]]
## Midterm 
#### LEC 1: [[V01-BinaryRepresentation.pdf]]
- [ ] [[Max & Min Values in k bits]]
- [ ] Powers of Two
- [ ] Decimal -> Binary Conversion
	- [ ] Repeated Division
	- [ ] Repeated Subtraction
- [ ] [[2-Complement Notation]]
- [ ] [[Sign Extension]]
#### LEC 2: [[V02-DataInMemory.pdf]]
- [ ] [[Hexadecimal]]
- [ ] Endianness
#### LEC3: [[V03-ComputerOrganizationMemoryAddressing.pdf]]
- [ ] [[Organization of a Computer]]
- [ ] [[Arithmetic Operations]]
- [ ]  C Code -> Assembly (Basic arithmetic operations)
	- A[0] = h + A[2], h <-> s2, A <-> s1
		- lw t0, 8(s1)
		- add t0, s2, t0
		- sw t0, 0(s1)
- [ ] Addressing an Integer Array
- [ ] [[Word]]
	- [ ] Word Alignment
- [ ] Registers vs Memory
- [ ] [[Immediate Operands]]
	- [ ] [[Make the common case fast]]



#### LEC 4 [[V04-MemoryRegisterDataTransfer.pdf]]
- [ ] sw, lw execution
- [ ] [[If else statement]]
- [ ] Representing Instructions
	- [ ] [[Parts of an instruction]]
	- [ ] [[Types of Instructions]]
	
#### LEC 5 [[V05-InstructionRepresentation.pdf]]
- [ ] [[Types of Instructions]]
- [ ] [[Unconditional jumps]]
- [ ] The Constant Zero

#### LEC 6 [[V06-LogicInstructions.pdf]]
- [ ] [[Logic Operations]]
- [ ] [[Binary to Decimal]] 
- [ ] [[Bitwise Logical Operations]]
	- [ ] RARS issue
- [ ] Load Immediate Instruction  (li)

#### LEC 7 [[V07-LargeConstants.pdf]]
- [ ] [[Large Constants]]
- [ ] Handling Large Constants in RARS
	- [ ] Pseudocode

#### LEC 8 [[V08-ArraysInMemory.pdf]]
- [ ] Arrays
	- [ ] x = A[i]
	- [ ] y = A[B[j]]]

#### LEC 9 [[V09-ConditionalInstructionsAndLoops.pdf]]
- [ ] Conditional Operations 
	- [ ] While Loops
- [ ] [[Non-Branch Comparison]] 
- [ ] [[Signed vs Unsigned Comparison]]
- [ ] Basic Blocks

#### LEC 10 [[V0A-IsBraExample.pdf]]
- [ ] Load Address (la)
- [ ] Program Organization
- [ ] IsBra Sample question

#### LEC 11 [[V0B-ProcedureCallsAndStack.pdf]]
- [ ] [[Callable Units]]
- [ ] Procedure Calls
	- [ ] Finding Return Address
		- [ ] Store Return address before calling
	- [ ] Problem
		- [ ] Single ra register
- [ ] [[Call Stacks]]
- [ ] Stack Pointer
- [ ] Saving Registers into the Stack
- [ ] Memory Layout
#### LEC 12 [[V0C-RegisterCallingConvention.pdf]]
- [ ] Register saving/restoring calling conventions
- [ ] [[Register Usage Conventions]]
- [ ] How is a function executed?
- [ ] Frame pointer   
 
#### LEC 13 [[V0D-RecursiveFunctions.pdf]]
- [ ] Recursive functions
- [ ] Non-Leaf Procedures
- [ ] Factorial Assembly Code 

#### LEC 14 [[V0E-StringsOfCharacters.pdf]]
- [ ] Instructions to Manipulate Characters
- [ ] Instructions to Manipulate Half Words
- [ ] Array Indexing
	- [ ] Integers
	- [ ] Characters
	- [ ] Doubles
	- [ ] Structures
		- [ ] Issues with structs (Data Alignment)
- [ ] String Copy (strcpy)
- [ ] jalr vs. jal (unconditional jump)

#### LEC 15 (EXTRA)
- [ ] GO BACK!!!

#### LEC 16 [[V0F-RelativePerformance.pdf]]
- [ ] [[Relative Performance]]
- [ ] [[Latency]]
- [ ] [[Throughput]]
- [ ] Measuring Time

#### LEC 17 [[V10-ClockAndFrequency.pdf]]
- [ ] [[CPU Clocking Formulas]]
#### LEC 18 [[V11-CPI.pdf]]
- [ ] CPI (Clock Per Instruction)

#### LEC 19 [[V12-PowerSPECAmdahl.pdf]]
- [ ] GO BACK !!!!

#### LEC 20 [[V13-BubbleSort.pdf]]
- [ ] Bubble Sort
	- [ ] Swap Procedure
	- [ ] Sort Procedure
	- [ ] Loop Template 
	- [ ] Bubble Sort Performance
		- [ ] Relative Performance
		- [ ] Clock Cycles
		- [ ] Instruction Count
		- [ ] CPI
	- [ ] Effect of Language and Algorithm

#### LEC 21 [[V14-FunctionCallInALoop.pdf]]
- [ ] Register Calling Conventions
- [ ] Data Flow  

#### LEC 22 [[V15-IndexingVsPointers.pdf]]
- [ ] Array Indexing vs. Pointers
	- [ ] End of indexing (size vs array + size*{4})
	- [ ] CPI vs actual performance

#### LEC 23 [[V16-StarP.pdf]]
- [ ] \*p

#### LEC 24 [[V1A-StringFunctions.pdf]]
- [ ] Examples of String Functions
	- [ ] strlen
	- [ ] Creating arrays of student names
	- [ ] maxlen
	- [ ] Array of Pointers to Pointers to Strings
- [ ] Types
	- [ ] \*char, \*\*char, \*\*\*char

#### LEC 25 [[V17-ExceptionsInterruptsPolling.pdf]]
- [ ] [[Exceptions]]
	- [ ] [[Handling Exceptions]]
	- [ ] What the OS needs to know
- [ ] Cause Register X Interrupt Vectors
- [ ] [[Interrupts]]
- [ ] [[Polling]]
- [ ] Interrupts vs. Polling

#### LEC 26 [[V18-ExceptionsRISC-V.pdf]]
- [ ] [[Control and Status Registers]]
- [ ] CSR instructions
	- [ ] [[Atomic Read-Modify-Write Operations]]
- [ ] RISC V Coprocessors
- [ ] [[Privilege Levels]]
	- [ ] Protection
	- [ ] Requesting Service
	- [ ] Context Switching
		- [ ] Costs
		- [ ] Synchronous, Asynchronous
		- [ ] [[printf]]
	- [ ] [[Trap Levels]]
- [ ]  [[Handling Exceptions]]
	- [ ] Exceptions Codes
	- [ ] Exception Handler
	- [ ] [[Re-entrant exception handler]]
## Final 

LEC 27 (V19)
- Non Re-entrant Exception Handler

LEC 28(V1B)
- [ ] Parameter Passing by Value
- [ ] Parameter Passing by Reference
	- [ ] Need to make a copy of the parameter
	- [ ] Print car vs. Read Card



























