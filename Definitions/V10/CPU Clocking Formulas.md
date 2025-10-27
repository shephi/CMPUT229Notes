
### Basic Formulas ---
$$
\text{Frequency} = \frac{\text{cycles}}{\text{second}}
$$
$$
\text{Clock cycle Time} = \frac{\text{seconds}}{\text{cycles}}
$$
$$
\text{Clock Cycle Time} = \frac{1}{\text{Frequency}}
$$
### Main Formulas ---

$$
\text{CPU Time} = {\text{num of CPU Cycles}}\times{\frac{\text{1}}{\text{Frequency}}}
$$
$$
\text{CPU Time} = \text{ num of CPU Cycles} \times \text{Clock Cycle Time}
$$
$$
\text{CPU Time} = \text{num of Instructions} \times \text{CPI} \times \text{Clock Cycle Time}
$$
$$
\text{CPI} = \frac{\text{Num of CPU Cycles}}{\text{Number of Instructions}}
$$
### Performance Summary ---
$$
\text{CPU Time} = \frac{\text{Instructions}}{\text{Program}} \times \frac{\text{Clock cycles}}{\text{Instruction}} \times \frac{\text{Seconds}}{\text{Clock Cycle}}
$$
$$
\text{CPU Time} = \text{Instruction Count} \times \text{CPI} \times \frac{1}{\text{Frequency}}
$$


- Ex. Two processors, A and B, are being compared based on their performance running the same program compiled with the same compiler with the same flags (binary of the program is identical for both processors).
- Processor A runs at 800 MHz and has an average CPI of 1.2 for this program.
- Processor B runs at 2 GHz and has an average CPI of 3.0 for the same program.
- Given these values, we can state that Processor B is faster than Processor A for this program.
- True or False?
1. *Find the Clock Cycle time for each processor*
	- Clock cycle time = 1/freq
	- Processor A
		- `800 MHz = 800 * 10^6 cycles/sec
		- Clock cycle time =` 1 /  800 * 10^6 = 1.25 ns
	- Processor B
		- `2 GHz = 2 * 10^9 cycles/sec
		- Clock Cycle time = `1/2 * 10^9 = 0.5ns
		- 
2. *Compute CPI x Clock Cycle Time *
	- Processor A: CPU Time =`1.2 ns * 1.25 ns per instruction
	- Processor B: CPU Time =`0.5 ns * 1.5 ns per instruction
**Formula Used:**
	1. `CPU Time = IC * Clock Cycle Time * CPI
	2. CPI is given, Clock Cycle Time = 1/freq
