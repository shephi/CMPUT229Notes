## Practice Material
- [[Introduction (Quiz 0)]](Definitions/Practice/Introduction (Quiz 0).md)

## Midterm

#### LEC 1: [[V01-BinaryRepresentation.pdf]](PDF Notes/V01-BinaryRepresentation.pdf)
- [ ] [[Max & Min Values in k bits]](Definitions/V01/Max & Min Values in k bits.md)
- [ ] Powers of Two
- [ ] Decimal -> Binary Conversion
  - [ ] Repeated Division
  - [ ] Repeated Subtraction
- [ ] [[2-Complement Notation]](Definitions/V01/2-Complement Notation.md)
- [ ] [[Sign Extension]](Definitions/V01/Sign Extension.md)

#### LEC 2: [[V02-DataInMemory.pdf]](PDF Notes/V02-DataInMemory.pdf)
- [ ] [[Hexadecimal to Decimal]](Definitions/V02/Hexadecimal to Decimal.md)
- [ ] Endianness

#### LEC 3: [[V03-ComputerOrganizationMemoryAddressing.pdf]](PDF Notes/V03-ComputerOrganizationMemoryAddressing.pdf)
- [ ] [[Organization of a Computer]](Definitions/V03/Organization of a Computer.md)
- [ ] [[Arithmetic Operations]](Definitions/V03/Arithmetic Operations.md)
- [ ] C Code -> Assembly (Basic arithmetic operations)
  - A[0] = h + A[2], h <-> s2, A <-> s1
    - lw t0, 8(s1)
    - add t0, s2, t0
    - sw t0, 0(s1)
- [ ] Addressing an Integer Array
- [ ] [[Word]](Definitions/V03/Word.md)
  - [ ] Word Alignment
- [ ] Registers vs Memory
- [ ] [[Immediate Operands]](Definitions/V03/Immediate Operands.md)
  - [ ] [[Make the common case fast]](Definitions/V03/Make the common case fast.md)

#### LEC 4: [[V04-MemoryRegisterDataTransfer.pdf]](PDF Notes/V04-MemoryRegisterDataTransfer.pdf)
- [ ] sw, lw execution in memory

#### LEC 5: [[V05-InstructionRepresentation.pdf]](PDF Notes/V05-InstructionRepresentation.pdf)
- [ ] [[If else statement]](Definitions/V05/If else statement.md)
- [ ] Representing Instructions
  - [ ] [[Parts of an instruction]](Definitions/V05/Parts of an instruction.md)
  - [ ] [[Types of Instructions]](Definitions/V05/Types of Instructions.md)
  - [ ] Instructions <-> Hexadecimal Representation
- [ ] [[Unconditional Jumps]](Definitions/V05/Unconditional Jumps.md)
- [ ] The Constant Zero

#### LEC 6: [[V06-LogicInstructions.pdf]](PDF Notes/V06-LogicInstructions.pdf)
- [ ] [[Logic Operations]](Definitions/V06/Logic Operations.md)
- [ ] [[Binary to Decimal]](Definitions/V06/Binary to Decimal.md)
- [ ] [[Bitwise Logical Operations]](Definitions/V06/Bitwise Logical Operations.md)
  - [ ] RARS issue
- [ ] Load Immediate Instruction (li)

#### LEC 7: [[V07-LargeConstants.pdf]](PDF Notes/V07-LargeConstants.pdf)
- [ ] [[Large Constants]](Definitions/V07/Large Constants.md)
- [ ] Handling Large Constants in RARS
  - [ ] Pseudocode

#### LEC 8: [[V08-ArraysInMemory.pdf]](PDF Notes/V08-ArraysInMemory.pdf)
- [ ] Arrays
  - [ ] `x = A[i]`
  - [ ] `y = A[B[j]]]`

#### LEC 9: [[V09-ConditionalInstructionsAndLoops.pdf]](PDF Notes/V09-ConditionalInstructionsAndLoops.pdf)
- [ ] Conditional Operations
  - [ ] While Loops
- [ ] [[Non-Branch Comparison]](Definitions/V09/Non-Branch Comparison.md)
- [ ] [[Signed vs Unsigned Comparison]](Definitions/V09/Signed vs Unsigned Comparison.md)
- [ ] Basic Blocks

#### LEC 10: [[V0A-IsBraExample.pdf]](PDF Notes/V0A-IsBraExample.pdf)
- [ ] Load Address (la)
- [ ] Program Organization
- [ ] IsBra Sample question

#### LEC 11: [[V0B-ProcedureCallsAndStack.pdf]](PDF Notes/V0B-ProcedureCallsAndStack.pdf)
- [ ] [[Callable Units]](Definitions/V0B/Callable Units.md)
- [ ] Procedure Calls
  - [ ] Finding Return Address
    - [ ] Store Return address before calling
  - [ ] Problem
    - [ ] Single ra register
- [ ] [[Call Stacks]](Definitions/V0B/Call Stacks.md)
- [ ] Stack Pointer
- [ ] Memory Layout

#### LEC 12: [[V0C-RegisterCallingConvention.pdf]](PDF Notes/V0C-RegisterCallingConvention.pdf)
- [ ] Register saving/restoring calling conventions
- [ ] [[Register Usage Conventions]](Definitions/V0C/Register Usage Conventions.md)
- [ ] [[Function Execution]](Definitions/V0C/Function Execution.md)
- [ ] Frame pointer

#### LEC 13: [[V0D-RecursiveFunctions.pdf]](PDF Notes/V0D-RecursiveFunctions.pdf)
- [ ] Recursive functions
- [ ] Non-Leaf Procedures
- [ ] Factorial Assembly Code

#### LEC 14: [[V0E-StringsOfCharacters.pdf]](PDF Notes/V0E-StringsOfCharacters.pdf)
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

#### LEC 16: [[V0F-RelativePerformance.pdf]](PDF Notes/V0F-RelativePerformance.pdf)
- [ ] [[Relative Performance]](Definitions/V0F/Relative Performance.md)
- [ ] [[Latency]](Definitions/V0F/Latency.md)
- [ ] [[Throughput]](Definitions/V0F/Throughput.md)
- [ ] Measuring Time

#### LEC 17: [[V10-ClockAndFrequency.pdf]](PDF Notes/V10-ClockAndFrequency.pdf)
- [ ] [[CPU Clocking Formulas]](Definitions/V10/CPU Clocking Formulas.md)

#### LEC 18: [[V11-CPI.pdf]](PDF Notes/V11-CPI.pdf)
- [ ] CPI (Clock Per Instruction)

#### LEC 19: [[V12-PowerSPECAmdahl.pdf]](PDF Notes/V12-PowerSPECAmdahl.pdf)
- [ ] GO BACK !!!!

#### LEC 20: [[V13-BubbleSort.pdf]](PDF Notes/V13-BubbleSort.pdf)
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

#### LEC 21: [[V14-FunctionCallInALoop.pdf]](PDF Notes/V14-FunctionCallInALoop.pdf)
- [ ] Register Calling Conventions
- [ ] Data Flow

#### LEC 22: [[V15-IndexingVsPointers.pdf]](PDF Notes/V15-IndexingVsPointers.pdf)
- [ ] Array Indexing vs. Pointers
  - [ ] End of indexing (size vs array + size*{4})
  - [ ] CPI vs actual performance

#### LEC 23: [[V16-StarP.pdf]](PDF Notes/V16-StarP.pdf)
- [ ] *p

#### LEC 24: [[V1A-StringFunctions.pdf]](PDF Notes/V1A-StringFunctions.pdf)
- [ ] Examples of String Functions
  - [ ] strlen
  - [ ] Creating arrays of student names
  - [ ] maxlen
  - [ ] Array of Pointers to Pointers to Strings
- [ ] Types
  - [ ] *char, **char, ***char

#### LEC 25: [[V17-ExceptionsInterruptsPolling.pdf]](PDF Notes/V17-ExceptionsInterruptsPolling.pdf)
- [ ] [[Exceptions]](Definitions/V17/Exceptions.md)
  - [ ] [[Handling Exceptions]](Definitions/V17/Handling Exceptions.md)
  - [ ] What the OS needs to know
- [ ] Cause Register X Interrupt Vectors
- [ ] [[Interrupts]](Definitions/V17/Interrupts.md)
- [ ] [[Polling]](Definitions/V17/Polling.md)
- [ ] Interrupts vs. Polling

#### LEC 26: [[V18-ExceptionsRISC-V.pdf]](PDF Notes/V18-ExceptionsRISC-V.pdf)
- [ ] [[Control and Status Registers]](Definitions/V18/Control and Status Registers.md)
- [ ] CSR instructions
  - [ ] [[Atomic Read-Modify-Write Operations]](Definitions/V18/Atomic Read-Modify-Write Operations.md)
- [ ] RISC V Coprocessors
- [ ] [[Privilege Levels]](Definitions/V18/Privilege Levels.md)
  - [ ] Protection
  - [ ] Requesting Service
  - [ ] Context Switching
    - [ ] Costs
    - [ ] Synchronous, Asynchronous
    - [ ] [[printf]](Definitions/V18/printf.md)
  - [ ] [[Trap Levels]](Definitions/V18/Trap Levels.md)
- [ ] [[Handling Exceptions]](Definitions/V18/Handling Exceptions.md)
  - [ ] Exceptions Codes
  - [ ] Exception Handler
  - [ ] [[Re-entrant exception handler]](Definitions/V18/Re-entrant exception handler.md)

## Final

#### LEC 27: [[V19-NonReentrantExceptionHandler.pdf]](PDF Notes/V19-NonReentrantExceptionHandler.pdf)
- Non Re-entrant Exception Handler

#### LEC 28: [[V1B-ParameterPassing.pdf]](PDF Notes/V1B-ParameterPassing.pdf)
- [ ] Parameter Passing by Value
- [ ] Parameter Passing by Reference
  - [ ] Need to make a copy of the parameter
  - [ ] Print car vs. Read Card
