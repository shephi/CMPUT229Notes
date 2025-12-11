- 1 bit for the sign (positive or negative)
- 8 bits for the range (exponent) field
- 23 bits for the precision (fraction field)

S | biased exponent | fraction

$$
N =
\begin{cases}
(-1)^S\times1.fraction\times2^{\text{biased exponent}-127}, 1\le\text{biased exponent} \le 254 \\
(-1)^S\times0.fraction\times2^{-126},\text{biased exponent} = 0
\end{cases} 
$$

