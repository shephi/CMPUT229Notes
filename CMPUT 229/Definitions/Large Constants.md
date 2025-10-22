- Load Immediate
- And 
- Shift 
lui t0, 0x00FF0

li t0, 0x0FF
slli t0, t0, 16

slli s1, s0, 8
srli, s1, s1, 24
