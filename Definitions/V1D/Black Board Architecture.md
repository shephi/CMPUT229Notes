- Ex. Newton Method: Calculate derivatives to find a local min
	- Problem: can only find local minimums

• **Lock Mechanism:** The sources illustrate using an atomic instruction pair (like `lr.w` and `sc.w` introduced in V1C) to acquire a lock variable (setting `lock = 1` atomically) before modifying shared data (`x` or `f(x)`).

• **Lock Success/Failure:** If a processor attempts to `sc.w lock = 1` and it succeeds (returns `t0 = 0`), it has the lock and can enter the critical section. If the `sc.w` fails (returns `t0 = !0`), another processor modified the lock in between the `lr.w` and `sc.w`, and the processor must retry.