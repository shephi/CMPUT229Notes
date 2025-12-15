- Forward Flow: Most signals and data flow logically from left to right (IF to WB)
- Backward Flows: The datapath must accomodate two critical flows moving backward or looping:
	1. **Write Back:** The final result needs to be written back to the **Registers** (ID stage)
	2. **Next PC:** The next value for the **PC** (IF stage) often comes from the computation of a branch target address (EX stage).