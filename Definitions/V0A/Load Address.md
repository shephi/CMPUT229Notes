- la r1, address:
``` asm-arm
auipc t0, %pcrel_hi(var)
addi  t0, t0, %pcrel_lo(var)
```
