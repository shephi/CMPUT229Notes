
- **Static Branch Prediction:**
	- Uses fixed rules, such as predicting backward branches (like loop ends) as taken and forward branches (like if checks) as not taken
- **Dynamic Branch Prediction:**
	- Uses specialized hardware (like a **Branch Prediction Buffer** or **Branch History Table**) indexed by bits from the PC and the recent history of branch outcomes. This hardware stores prediction results to assume future behavior will follow the trend
- **Branch Target Buffer (BTB):**
	- A cache of target addresses used to predict the address of taken branch immediately upon instruction fetch, bypassing the calculation delay 