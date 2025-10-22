## Practice Material
- [[Introduction (Quiz 0)]]
## Midterm 
#### LEC 1 (V01)
- [ ] [[Max & Min Values in k bits]]
- [ ] Powers of Two
- [ ] Decimal -> Binary Conversion
	- [ ] Repeated Division
	- [ ] Repeated Subtraction
- [ ] [[2-Complement Notation]]
- [ ] [[Sign Extension]]
#### LEC 2 (V02)
- [ ] [[Hexadecimal]]
- [ ] Endianness
#### LEC 3 (V03)
- [ ] [[Organization of a Computer]]
- [ ] Arithmetic Operations
	- [ ] add a, b, c
	- [ ] addi a, b, 20
	- [ ] sub a, b, c
	- [ ] addi a, b, -20
- [ ] C Code -> Assembly (Basic arithmetic operations)
	- A[0] = h + A[2], h <-> s2, A <-> s1
		- lw t0, 8(s1)
		- add t0, s2, t0
		- sw t0, 0(s1)
- [ ] Immediate Operands
- [ ] Memory Operands
- [ ] Addressing an Integer Array
- [ ] Word
	- [ ] Load Word (lw)
	- [ ] Store Word (sw)
	- [ ] Word Alignment
- [ ] C code -> Assembly (Store and Load Words)
	- [ ] Displacement
- [ ] Registers vs Memory
- [ ] Design Principle (Make the common case Fast)

#### LEC 4 (V04)
- [ ] sw, lw execution
- [ ] [[If else statement]]
- [ ] Representing Instructions
	- [ ] Parts of an instruction
		- [ ] Opcode (op)
		- [ ] function code (funct7)
		- [ ] function code (funct3)
		- [ ] rd (register destination)
		- [ ] rs1 (first register source)
		- [ ] rs2 (second register source)
	- [ ] Types
		- [ ] R-Type
		- [ ] I-Type
		- [ ] S-Type
		- [ ] U-Type
#### LEC 5 (V05)
- [ ] SB- Type
- [ ] [[Unconditional jumps]]
	- [ ] jal
	- [ ] jalr
- [ ] The Constant Zero
- [ ] UJ-Type

#### LEC 6 (V06)
- [ ] [[Logic Operations]]
	- [ ] slli
	- [ ] srli
	- [ ] srai
	- [ ] sll
	- [ ] srl
	- [ ] sra
- [ ] [[Binary to Decimal]] 
- [ ] Bitwise Logical Operations
	- [ ] and 
	- [ ] or
	- [ ] xor
	- [ ] xori
- [ ] Bitwise with immediate operand
	- [ ] RARS issue
- [ ] Load Immediate Instruction  (li)

#### LEC 7 (V07)
- [ ] [[Large Constants]]
- [ ] Handling Large Constants in RARS
	- [ ] Pseudocode

#### LEC 8 (V08)
- [ ] Arrays
	- [ ] x = A[i]
	- [ ] y = A[B[j]]]

#### LEC 9 (V09)
- [ ] Conditional Operations 
	- [ ] While Loops
- [ ] [[Non-Branch Comparison]] 
- [ ] Signed vs Unsigned Comparison
	- [ ] Signed Comparison: slt, slti
	- [ ] Unsigned Comparison: sltu, sltiu
- [ ] Basic Blocks

#### LEC 10 (V0A)
- [ ] Load Address (la)
- [ ] Program Organization
- [ ] IsBra Sample question

#### LEC 11 (V0B)
- [ ] Callable Units
	- [ ] Procedure
	- [ ] Function
	- [ ] Rountine
	- [ ] Subroutine
	- [ ] Subprogram
	- [ ] Method
- [ ] Procedure Calls
	- [ ] Finding Return Address
		- [ ] Store Return address before calling
	- [ ] Problem
		- [ ] Single ra register
- [ ] Call Stacks
	- [ ] Value of fp
	- [ ] Value of ra
	- [ ] Registers that are modified by function
	- [ ] Local Variables
- [ ] Stack Pointer (sp) Register
- [ ] Saving Registers into the Stack
- [ ] Memory Layout


#### LEC 12 (V0C)
- [ ] Register saving/restoring calling conventions
- [ ] Register Usage Conventions
- [ ] How is a function executed?
- [ ] Frame pointer   
 
#### LEC 13 (V0D)
- [ ] Recursive functions
- [ ] Non-Leaf Procedures
- [ ] Factorial Assembly Code 

#### LEC 14 (V0E)
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

#### LEC 16 (V0F)
- [ ] [[Relative Performance]]
- [ ] [[Latency]]
- [ ] [[Throughput]]
- [ ] Measuring Time

#### LEC 17 (V10)
- [ ] [[CPU Clocking Formulas]]
#### LEC 18 (V11)
- [ ] CPI (Clock Per Instruction)

#### LEC 19 (V12)
- [ ] GO BACK !!!!

#### LEC 20 (V13)
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

#### LEC 21 (V14)
- [ ] Register Calling Conventions
- [ ] Data Flow  

#### LEC 22 (V15)
- [ ] Array Indexing vs. Pointers
	- [ ] End of indexing (size vs array + size*{4})
	- [ ] CPI vs actual performance

#### LEC 23 (V16)
- [ ] \*p

#### LEC 24 (V1A)
- [ ] Examples of String Functions
	- [ ] strlen
	- [ ] Creating arrays of student names
	- [ ] maxlen
	- [ ] Array of Pointers to Pointers to Strings
- [ ] Types
	- [ ] \*char, \*\*char, \*\*\*char

#### LEC 25 (V17)
- [ ] [[Exceptions]]
	- [ ] [[Handling Exceptions]]
	- [ ] What the OS needs to know
- [ ] Cause Register X Interrupt Vectors
- [ ] [[Interrupts]]
- [ ] [[Polling]]
- [ ] Interrupts vs. Polling

#### LEC 26 (V18)
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



























