```
lw t0, 8(s1)
add
sw t0, 0(s1)
```

lw t0, 8(s1):
1. PC sends address of instruction to be read from memory through the control bus
2. Processor sends to control bus it is a read instruction
3. PC increments automatically by 4 for next instruction
4. Memory sends instruction data at address given by the PC to the Instruction Register through the data bus
5. Instruction Register decodes the instruction
6. ALU calculates the displacement of the read operation
7. Processor sends displaced address through the address bus
8. Processor sends through the control bus that it is a read operation
9. Memory sends through the data bus the data at the correct memory address and stores in the correct register in the processor

