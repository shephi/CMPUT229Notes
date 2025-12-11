
> [!NOTE] Steps
> $$9.999_{10} \times 10^1 + 1.610_{10} \times 10^{-1}$$
> 1. Align the decimal point
> 	- The exponent of the number with the smaller exponent must be adjusted to match the larger exponent
> 	- Usually requires shifting the significand of the smaller number -> loss of precision
> 	$$9.999_{10} \times 10^1 + 0.0016_{10} \times 10^1$$
> 2. Add the significands
> 	$$9.999_{10} \times 10^1 + 0.016_{10} \times 10^1 = 10.015_{10} \times 10^1$$
> 3. Renormalize the result
> 	$$10.015 \times 10^1 = 1.0015 \times 10^2$$
> 4. Round-off the result
> 	$$1.0015 \times 10^2 = 1.002 \times 10^2 $$
