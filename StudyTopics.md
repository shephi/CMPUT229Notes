## Practice Material
- [[Introduction (Quiz 0)]](Definitions/Practice/Introduction%20(Quiz%200).md)

## Midterm 

#### LEC 1: ![[V01-BinaryRepresentation.pdf]](PDF Notes/V01-BinaryRepresentation.pdf)
- [ ] [[Max & Min Values in k bits]](Definitions/V01/Max%20&%20Min%20Values%20in%20k%20bits.md)
- [ ] Powers of Two
- [ ] Decimal -> Binary Conversion
	- [ ] Repeated Division
	- [ ] Repeated Subtraction
- [ ] [[2-Complement Notation]](Definitions/V01/2-Complement%20Notation.md)
- [ ] [[Sign Extension]](Definitions/V01/Sign%20Extension.md)

#### LEC 2: [[V02-DataInMemory.pdf]](PDF%Notes/V02-DataInMemory.pdf)
- [ ] [[Hexadecimal to Decimal]](Definitions/V02/Hexadecimal%20to%20Decimal.md)
- [ ] Endianness

#### LEC 3: [[V03-ComputerOrganizationMemoryAddressing.pdf]](PDF%Notes/V03-ComputerOrganizationMemoryAddressing.pdf)
- [ ] [[Organization of a Computer]](Definitions/V03/Organization%20of%20a%20Computer.md)
- [ ] [[Arithmetic Operations]](Definitions/V03/Arithmetic%20Operations.md)
- [ ]  C Code -> Assembly (Basic arithmetic operations)
	- A[0] = h + A[2], h <-> s2, A <-> s1
		- lw t0, 8(s1)
		- add t0, s2, t0
		- sw t0, 0(s1)
- [ ] Addressing an Integer Array
- [ ] [[Word]](Definitions/V03/Word.md)
	- [ ] Word Alignment
- [ ] Registers vs Memory
- [ ] [[Immediate Operands]](Definitions/V03/Immediate%20Operands.md)
	- [ ] [[Make the common case fast]](Definitions/V03/Make%20the%20common%20case%20fast.md)

#### LEC 4: [[V04-MemoryRegisterDataTransfer.pdf]](PDF%Notes/V04-MemoryRegisterDataTransfer.pdf)
- [ ] sw, lw execution in memory

#### LEC 5: [[V05-InstructionRepresentation.pdf]](PDF%Notes/V05-InstructionRepresentation.pdf)
- [ ] [[If else statement]](Definitions/V05/If%20else%20statement.md)
- [ ] Representing Instructions
	- [ ] [[Parts of an instruction]](Definitions/V05/Parts%20of%20an%20instruction.md)
	- [ ] [[Types of Instructions]](Definitions/V05/Types%20of%20Instructions.md)
	- [ ] Instructions <-> Hexadecimal Representation
- [ ] [[Unconditional Jumps]](Definitions/V05/Unconditional%20Jumps.md)
- [ ] The Constant Zero

#### LEC 6: [[V06-LogicInstructions.pdf]](PDF%Notes/V06-LogicInstructions.pdf)
- [ ] [[Logic Operations]](Definitions/V06/Logic%20Operations.md)
- [ ] [[Binary to Decimal]](Definitions/V06/Binary%20to%20Decimal.md)
- [ ] [[Bitwise Logical Operations]](Definitions/V06/Bitwise%20Logical%20Operations.md)
	- [ ] RARS issue
- [ ] Load Immediate Instruction (li)

#### LEC 7: [[V07-LargeConstants.pdf]](PDF%Notes/V07-LargeConstants.pdf)
- [ ] [[Large Constants]](Definitions/V07/Large%20Constants.md)
- [ ] Handling Large Constants in RARS
	- [ ] Pseudocode

#### LEC 8: [[V08-ArraysInMemory.pdf]](PDF%Notes/V08/V08-ArraysInMemory.pdf)
- [ ] Arrays
	- [ ] `x = A[i]`
	- [ ] `y = A[B[j]]]`

#### LEC 9: [[V09-ConditionalInstructionsAndLoops.pdf]](PDF Notes/V09/V09-ConditionalInstructionsAndLoops.pdf)
- [ ] Conditional Operations 
	- [ ] While Loops
- [ ] [[Non-Branch Comparison]](Definitions/V09/Non-Branch%20Comparison.md)
- [ ] [[Signed vs Unsigned Comparison]](Definitions/V09/Signed%20vs%20Unsigned%20Comparison.md)
- [ ] Basic Blocks

#### LEC 10: [[V0A-IsBraExample.pdf]](PDF Notes/V0A/V0A-IsBraExample.pdf)
- [ ] Load Address (la)
- [ ] Program Organization
- [ ] IsBra Sample question

#### LEC 11: [[V0B-ProcedureCallsAndStack.pdf]](PDF Notes/V0B/V0B-ProcedureCallsAndStack.pdf)
- [ ] [[Callable Units]](Definitions/V0B/Callable%20Units.md)
- [ ] Procedure Calls
	- [ ] Finding Return Address
		- [ ] Store Return address before calling
	- [ ] Problem
		- [ ] Single ra register
- [ ] [[Call Stacks]](Definitions/V0B/Call%20Stacks.md)
- [ ] Stack Pointer
- [ ] Memory Layout

#### LEC 12: [[V0C-RegisterCallingConvention.pdf]](PDF Notes/V0C/V0C-RegisterCallingConvention.pdf)
- [ ] Register saving/restoring calling conventions
- [ ] [[Register Usage Conventions]](Definitions/V0C/Register%20Usage%20Conventions.md)
- [ ] [[Function Execution]](Definitions/V0C/Function%20Execution.md)
- [ ] Frame pointer   

#### LEC 13: [[V0D-RecursiveFunctions.pdf]](PDF Notes/V0D/V0D-RecursiveFunctions.pdf)
- [ ] Recursive functions
- [ ] Non-Leaf Procedures
- [ ] Factorial Assembly Code 

#### LEC 14: [[V0E-StringsOfCharacters.pdf]](PDF Notes/V0E/V0E-StringsOfCharacters.pdf)
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

#### LEC 16: [[V0F-RelativePerformance.pdf]](PDF Notes/V0F/V0F-RelativePerformance.pdf)
- [ ] [[Relative Performance]](Definitions/V0F/Relative%20Performance.md)
- [ ] [[Latency]](Definitions/V0F/Latency.md)
- [ ] [[Throughput]](Definitions/V0F/Throughput.md)
- [ ] Measuring Time

#### LEC 17: [[V10-ClockAndFrequency.pdf]](PDF Notes/V10/V10-ClockAndFrequency.pdf)
- [ ] [[CPU Clocking Formulas]](Definitions/V10/CPU%20Clocking%20Formulas.md)

#### LEC 18: [[V11-CPI.pdf]](PDF Notes/V11/V11-CPI.pdf)
- [ ] CPI (Clock Per Instruction)

#### LEC 19: [[V12-PowerSPECAmdahl.pdf]](PDF Notes/V12/V12-PowerSPECAmdahl.pdf)
- [ ] GO BACK !!!!

#### LEC 20: [[V13-BubbleSort.pdf]](PDF Notes/V13/V13-BubbleSort.pdf)
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

#### LEC 21: [[V14-FunctionCallInALoop.pdf]](PDF Notes/V14/V14-FunctionCallInALoop.pdf)
- [ ] Register Calling Conventions
- [ ] Data Flow  

#### LEC 22: [[V15-IndexingVsPointers.pdf]](PDF Notes/V15/V15-IndexingVsPointers.pdf)
- [ ] Array Indexing vs. Pointers
	- [ ] End of indexing (size vs array + size*{4})
	- [ ] CPI vs actual performance

#### LEC 23: [[V16-StarP.pdf]](PDF Notes/V16/V16-StarP.pdf)
- [ ] \*p

#### LEC 24: [[V1A-StringFunctions.pdf]](PDF Notes/V1A/V1A-StringFunctions.pdf)
- [ ] Examples of String Functions
	- [ ] strlen
	- [ ] Creating arrays of student names
	- [ ] maxlen
	- [ ] Array of Pointers to Pointers to Strings
- [ ] Types
	- [ ] \*char, \*\*char, \*\*\*char

#### LEC 25: [[V17-ExceptionsInterruptsPolling.pdf]](PDF Notes/V17/V17-ExceptionsInterruptsPolling.pdf)
- [ ] [[Exceptions]](Definitions/V17/Exceptions.md)
	- [ ] [[Handling Exceptions]](Definitions/V17/Handling%20Exceptions.md)
	- [ ] What the OS needs to know
- [ ] Cause Register X Interrupt Vectors
- [ ] [[Interrupts]](Definitions/V17/Interrupts.md)
- [ ] [[Polling]](Definitions/V17/Polling.md)
- [ ] Interrupts vs. Polling

#### LEC 26: [[V18-ExceptionsRISC-V.pdf]](PDF Notes/V18/V18-ExceptionsRISC-V.pdf)
- [ ] [[Control and Status Registers]](Definitions/V18/Control%20and%20Status%20Registers.md)
- [ ] CSR instructions
	- [ ] [[Atomic Read-Modify-Write Operations]](Definitions/V18/Atomic%20Read-Modify-Write%20Operations.md)
- [ ] RISC V Coprocessors
- [ ] [[Privilege Levels]](Definitions/V18/Privilege%20Levels.md)
	- [ ] Protection
	- [ ] Requesting Service
	- [ ] Context Switching
		- [ ] Costs
		- [ ] Synchronous, Asynchronous
		- [ ] [[printf]](Definitions/V18/printf.md)
	- [ ] [[Trap Levels]](Definitions/V18/Trap%20Levels.md)
- [ ]  [[Handling Exceptions]](Definitions/V18/Handling%20Exceptions.md)
	- [ ] Exceptions Codes
	- [ ] Exception Handler
	- [ ] [[Re-entrant exception handler]](Definitions/V18/Re-entrant%20exception%20handler.md)

## Final 

#### LEC 27: [[V19-ExceptionHandlerExample.pdf]](Definitions/V19/V19-NonReentrantExceptionHandler.pdf)
- Non Re-entrant Exception Handler

#### LEC 28: [[V1B-ValueVsReferenceParameterPassing.pdf]](Definitions/V1B/V1B-ParameterPassing.pdf)
- [ ] Parameter Passing by Value
- [ ] Parameter Passing by Reference
	- [ ] Need to make a copy of the parameter
	- [ ] Print car vs. Read Card
