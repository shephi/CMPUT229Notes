Ex. Processor requests word at address 0xFF00 0028
1. Extract the index: 
	- 0xFF00 **002**8
2. Extract the tag:
	- 0x**FF00** 0028
3. Check the Cache
	- The CPU accesses the specific index location from step 1
4. Verification
	- A hit occurs only if two conditions are met:
		- The **Valid Bit** associated with that entry is **1**
		- The stored **Tag** matches the **Tag** derived from the **requested memory address**