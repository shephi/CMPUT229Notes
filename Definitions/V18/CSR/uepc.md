Address of instruction that caused exception
1. Saves the address of the faulting instruction (or the next instruction to execute) in the **UEPC** register.
2. Jumps to the trap handler (the piece of code that will handle the exception).
3. After the handler finishes, it can restore the program counter from **UEPC** to resume normal execution.