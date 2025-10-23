## Practice Material
- [[Introduction (Quiz 0)]]
### Programming Questions
- [ ] *Practice Questions*
	- [ ] 31. Flow Analysis, Instruction Decode, Load-Use Dependence Detection
		- [ ] [[F23-final-A1-Q6.pdf]] -> [[F23-final-A1-Q6-sol.pdf]]
	- [ ] 32. Reverse the value of an Integer
		- [ ] [[F23-midterm-A1-Q5.pdf]] -> [[F23-midterm-A1-Q5-sol.pdf]]
	- [ ] 33. Print all Numerical Palindromes in an Interval
		- [ ] [[F23-midterm-A1-Q6.pdf]] -> [[F23-midterm-A1-Q6-sol.pdf]]
	- [ ] 34. Reverse a String
		- [ ] [[F19-midterm-A2-Q5.pdf]] -> [[F19-midterm-A2-Q6-sol.pdf]]
	- [ ] 35. Reverse multiple Strings
		- [ ] [[F19-midterm-A2-Q6.pdf]] -> [[F19-midterm-A2-Q6-sol.pdf]]
## Midterm 
#### LEC 1: [[V01-BinaryRepresentation.pdf]]
- [ ] [[Max & Min Values in k bits]]
- [ ] Powers of Two
- [ ] Decimal -> Binary Conversion
	- [ ] Repeated Division
	- [ ] Repeated Subtraction
- [ ] [[2-Complement Notation]]
- [ ] [[Sign Extension]]
- [ ] *Practice Questions*
	- [ ] 28. Binary vs Decimal Conversion, Overflow
		- [ ] [[Q2-midtermF10.pdf]] -> [[Q2-midtermF10-sol.pdf]]
#### LEC 2: [[V02-DataInMemory.pdf]]
- [ ] [[Hexadecimal to Decimal]]
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
- [ ] *Practice Questions*
	- [ ] 19. [[F10-Midterm-Q2.pdf]] -> [[F10-Midterm-Q2-sol.pdf]]
	- [ ] 
#### LEC 4 [[V04-MemoryRegisterDataTransfer.pdf]]
- [ ] sw, lw execution in memory
#### LEC 5 [[V05-InstructionRepresentation.pdf]]
- [ ] [[If else statement]]
- [ ] Representing Instructions
	- [ ] [[Parts of an instruction]]
	- [ ] [[Types of Instructions]]
	- [ ] Instructions <-> Hexadecimal Representation
- [ ] [[Unconditional Jumps]]
- [ ] The Constant Zero
- [ ] *Practice Questions*:
	- [ ] 12. Branches, Addresses Displacements
		- [ ] [[F10-quiz2.pdf]] -> [[F10-quiz2-sol.pdf]]
	- [ ] 14. Instruction Decoding
		- [ ] [[W25-midterm-B1-Q5.pdf]] -> [[W25-midterm-B1-Q5-sol.pdf]]
	- [ ] 17. Instruction Binary Representation
		- [ ] [[W25-midterm-B1-Q4.pdf]] -> [[W25-midterm-B1-Q4-sol.pdf]]
	- [ ] 18. Load Word Indirect
		- [ ] [[f16-midterm-q2.pdf]] -> [[f16-midterm-q2-sol.pdf]]
	- [ ] 24. UJ-Type and SB-Type Instructions
		- [ ] [[F23-midterm-A1-Q3.pdf]] -> [[F23-midterm-A1-Q3-sol.pdf]]
	- [ ] 25. SB-Type Instruction Format
		- [ ] [[F19-midterm-A2-Q1.pdf]] -> [[F19-midterm-A2-Q1-sol.pdf]]
	- [ ] 26. SB-Type Instruction Format
		- [ ] [[F19-midterm-A1-Q1.pdf]] -> [[F19-midterm-A1-Q1-sol.pdf]]
	- [ ] 29. Large Register File
		- [ ] [[F13-finalA2-Q4.pdf]] -> [[F13-finalA2-Q4-sol.pdf]]
	- [ ] 30. Representation of Jal and Branch Instructions
		- [ ] [[W12-quiz3.pdf]] -> [[W12-quiz3-sol.pdf]]
#### LEC 6 [[V06-LogicInstructions.pdf]]
- [ ] [[Logic Operations]]
- [ ] [[Binary to Decimal]] 
- [ ] [[Bitwise Logical Operations]]
	- [ ] RARS issue
- [ ] Load Immediate Instruction  (li)
- [ ] *Practice Questions*
	- [ ] 13. Analysis of Instructions
		- [ ]  [[f13-quiz1-a2-b.pdf]] -> [[f13-quiz1-a2-b-sol.pdf]]
	- [ ] 15. Scanning Instructions
		- [ ] [[W25-midterm-B1-Q6.pdf]] -> [[W25-midterm-B1-Q6-sol.pdf]]

#### LEC 7 [[V07-LargeConstants.pdf]]
- [ ] [[Large Constants]]
- [ ] Handling Large Constants in RARS
	- [ ] Pseudocode
- [ ] *Practice Questions*
	- [ ] 22. Shift Instructions
		- [ ] [[W17-midterm-A1-Q1.pdf]] -> [[W17-midterm-A1-Q1-sol.pdf]]
	- [ ] 27. Multiplication, Performance Estimate
		- [ ] [[F10-quiz4.pdf]] -> [[F10-quiz4-sol.pdf]]
#### LEC 8 [[V08-ArraysInMemory.pdf]]
- [ ] Arrays
	- [ ] `x = A[i]`
	- [ ] `y = A[B[j]]]`
- [ ] *Practice Questions*
	- [ ] 20. String Processor
		- [ ] [[F17-midterm-A1-Q1.pdf]] -> [[F17-midterm-A1-Q1-sol.pdf]]
	- [ ] 21. Array Access and Logic Instructions
		- [ ] [[F17-midterm-A2-Q1.pdf]] -> [[F17-midterm-A2-Q1-sol.pdf]]
	- [ ] 23. Array Accesses
		- [ ] [[F23-midterm-A1-Q1.pdf]] -> [[F23-midterm-A1-Q1-sol.pdf]]
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
- [ ] Memory Layout
#### LEC 12 [[V0C-RegisterCallingConvention.pdf]]
- [ ] Register saving/restoring calling conventions
- [ ] [[Register Usage Conventions]]
- [ ] [[Function Execution]]
- [ ] Frame pointer   
- [ ] 42. Function Creation
	- [ ] [[F17-midterm-A2-Q4.pdf]] -> [[F17-midterm-A2-Q4-sol.pdf]]
#### LEC 13 [[V0D-RecursiveFunctions.pdf]]
- [ ] Recursive functions
- [ ] Non-Leaf Procedures
- [ ] Factorial Assembly Code 
- [ ] *Practice Questions*
	- [ ] 16. Recursion, Branches
		- [ ] [[W25-midterm-B1-Q3.pdf]] -> [[W25-midterm-B1-Q3-sol.pdf]]
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
- [ ] *Practice Questions*
	- [ ] 41. Multi-field Structures and Function Calls
		- [ ] [[F14-final-Q4.pdf]] -> [[F14-final-Q4-sol.pdf]]
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
- [ ] *Practice Questions*
	- [ ] 47. Main Memory Access Time
		- [ ] [[F23-final-A1-Q5.pdf]] -> [[F23-final-A1-Q5-sol.pdf]]
	- [ ] 48. CPI
		- [ ] [[F19-midterm-A2-Q2.pdf]] -> [[F19-midterm-A2-Q2-sol.pdf]]
	- [ ] 49. CPI and Speedup
		- [ ] [[F17-midterm-A2-Q2.pdf]] -> [[F17-midterm-A2-Q2-sol.pdf]]
	- [ ] 50. CPI, Speedup, Clock Frequency
		- [ ] [[F17-final-A1-Q4.pdf]] -> [[F17-final-A1-Q4-sol.pdf]]
	- [ ] 51. Memory Hierarchy
		- [ ] [[F19-final-A1-Q5.pdf]] -> [[F19-final-A1-Q5-sol.pdf]] 
	- [ ] 53. CPI, Relative Performance
		- [ ] [[W14-midterm-Q3.pdf]] -> [[W14-midterm-Q3-sol.pdf]]
	- [ ] 54. Instructions, compilers
		- [ ] [[W14-quiz2-A.pdf]] -> [[W14-quiz2-A-sol.pdf]]
	- [ ] 55. Instructions, compilers
		- [ ] [[W14-quiz2-B.pdf]] -> [[W14-quiz2-B-sol.pdf]]
	- [ ] 57. CPI 
		- [ ] [[F13-midterm-A1-Q5.pdf]] -> [[F13-midterm-A1-Q5-sol.pdf]]
	- [ ] 59. Multiple Compilers
		- [ ] [[W12-quiz2.pdf]] -> [[W12-quiz2-sol.pdf]]
	- [ ] 61. CPI, relative performance
		- [ ] [[Q4-midtermF11.pdf]] -> [[Q4-midtermF11-sol.pdf]]
	- [ ] 62. CPI
		- [ ] [[F11-quiz2.pdf]] -> [[F11-quiz2-sol.pdf]]
	- [ ] 63. CPI, Execution Time, Speedup
		- [ ] [[Q1-midtermF10.pdf]] -> [[Q1-midtermF10-sol.pdf]]
	- [ ] 64. CPI, Relative Performance
		- [ ] [[F11-Midterm-Q4.pdf]] -> [[F11-Midterm-Q4-sol.pdf]]
	- [ ] 65. Performance Analysis
		- [ ] [[F14-midterm-Q2.pdf]] -> [[F14-midterm-Q2-sol.pdf]]
	- [ ] 66. CPI
		- [ ] [[HW2-Q1.pdf]] -> [[HW2-Q1-sol.pdf]]
	- [ ] 67. CPI, Relative Performance
		- [ ] [[F23-midterm-A1-Q2.pdf]] -> [[F23-midterm-A1-Q2-sol.pdf]]
#### LEC 19 [[V12-PowerSPECAmdahl.pdf]]
- [ ] GO BACK !!!!
- [ ] *Practice Questions*
	- [ ] 46. CPI, Ahmdal's Law
		- [ ] [[W25-midterm-B1-Q1.pdf]] -> [[W25-midterm-B1-Q1-sol.pdf]]

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
- [ ] *Practice Questions*
	- [ ] 37. Pointers
		- [ ] [[W25-midterm-B1-Q2.pdf]] -> [[W25-midterm-B1-Q2-sol.pdf]]
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
- [ ] *Practice Questions*
	- [ ] 38. Sorting Strings, Pointers
		- [ ] [[F19-final-A2-Q5.pdf]] -> [[F19-final-A2-Q5-sol.pdf]]
	- [ ] 39. String Manipulation
		- [ ] [[F19-final-A1-Q6.pdf]] -> [[F19-final-A1-Q6-sol.pdf]]
	- [ ] 40. Bit Manipulation & String Manipulation
		- [ ] [[F16-midterm-Q4.pdf]] -> [[F16-midterm-Q4-sol.pdf]]
	- [ ] 45. Pointers
		- [ ] [[F23-midterm-A1-Q4.pdf]] -> [[F23-midterm-A1-Q4-sol.pdf]]
#### LEC 25 [[V17-ExceptionsInterruptsPolling.pdf]]
- [ ] [[Exceptions]]
	- [ ] [[Handling Exceptions]]
	- [ ] What the OS needs to know
- [ ] Cause Register X Interrupt Vectors
- [ ] [[Interrupts]]
- [ ] [[Polling]]
- [ ] Interrupts vs. Polling
- [ ] *Practice Questions*
- [ ] 44. Pointers 
	- [ ] [[W15-HW3-Q4.pdf]] -> [[W15-HW3-Q4-sol.pdf]]
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
