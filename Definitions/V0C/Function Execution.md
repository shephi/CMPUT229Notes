A function cannot be executed unless it is called by another function
- Every function is a **callee**
- Every function must preserve the original value of the **s registers**
	Ex. Main function is called by a runtime system function
		main is callee: without a call main would never execute
- **Leaf Functions** do not call another function
	- Leaf functions are not callers