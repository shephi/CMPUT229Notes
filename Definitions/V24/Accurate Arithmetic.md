- Guard Digit, Round Digit:
	- Extra bits of precision added to the standard fraction (significand) during intermediate steps of arithmetic, such as floating-point addition
	- Holds the most significant bits that fall off the end of the standard mantissa
	- Guard Digit: Stores the first digit/bit shifted out of the standard mantissa
	- Round Digit: Stores the second digit/bit shifted out of the standard mantissa
- Sticky Bit:
	- Used to improve the accuracy of rounding, particularly when the value falls exactly at the midpoint between two representable numbers


> [!NOTE] Example
> $$\text{Add } 2.56_{10} \times 10^0 \text{ to } 2.34_{10} \times 10^2$$
> 1. Alignment (Shift number with smaller exponent)
> $$2.56_{10} \rightarrow 0.0256_{10} \times 10^2$$
> $$\text{Stored Value: 0 0 2 . 5 6} $$
> 2. Addition 
> $$0.0256 + 2.3400 = 2.3656$$
> $$\text{Stored result: 2 3 6 . 5 6} $$
> 3. Renormalization (This value is already normalized)
> $$2.3656$$
> 4. Rounding 
> $$2.37 \times 10^2$$


> [!NOTE] Example with no Sticky Bit
> Round 50 to the nearest even
> $$5.01_{10} \times 10^{-1} + 2.34_{10} \times 10^2 = 2.34$$



> [!NOTE] Example with Sticky Bit
> Sticky Bit = 1, 50 is rounded up, Sticky Bit = 0, round to nearest even
> $$5.01_{10} \times 10^{-1} + 2.34_{10} \times 10^2 = 2.35$$
