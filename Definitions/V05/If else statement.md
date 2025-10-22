```c
if (i == j)
	f = g + h;
else
	f = g - h
```


> [!NOTE] Assumptions
> - f <-> s0
> - g <-> s1
> - h <-> s2
> - i <-> s3
> - j <-> s4


```
	bne s3, s4, Subtract // if i != j goto Subtract
	add s0, s1, s2 // if f <- g + h
	jal zero, Exit // goto Exit
Subtract: sub, s0, s1, s2 // f <- g - h
Exit:
```
