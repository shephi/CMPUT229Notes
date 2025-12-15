RISC-V instruction set architecture is well-suited for pipelining because:
- All instructions are a fixed 32-bit ls long, (simplifies fetch and decoding steps)
- Few and regular instruction formats (allows single stage decoding and reading)
- Load/Store addressing mode is structured so that the memory address can be fully calculated early (EX stage) allowing the memory access stage (MEM stage) to happen immediately afterward