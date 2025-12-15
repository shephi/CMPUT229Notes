- Allow CPU to execute instructions out of order to avoid stalls but commit result to registers in order
- Ex.
```
ld x31, 0x(21)
add x1, x31, x2
sub x23, x23, x3
andi x5, x23, 20
# Can start sub while add is waiting for ld
```
- Instruction Flow: Instructions are issued into structures like **reservation stations** where they wait for their operands to become available
- Execution Order: Instructions can execute out of order based on when their inputs are ready
	- For example, a subsequent, unrelated instruction (sub) can start executing while a preceding instruction (add) waits for data being loaded from memory (ld)
- Commitment Order: Despite out-of-order execution, results, are buffered in a **Reorder Buffer**  and miust commit (write back to the architectural registers) in the original **program order** to maintain precise state
- 