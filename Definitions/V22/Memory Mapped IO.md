- Use a memory address to access an I/O register
- Address decode captures I/O accesses
- OS ensures that IO mapped addresses are only accessible to kernel

- Allows interaction with external devices through an interface pretending to be system memory
- This mapping allows the processor to communicate with these devices using load-word and store-word instructions. 