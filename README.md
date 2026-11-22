# Tiny Stack VM

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/lions0810/tiny-stack-vm-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/lions0810/tiny-stack-vm-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

An entry to make.fun's ["Build a tiny stack virtual machine" bounty](https://make.fun/bounty/tiny-stack-vm-01-run-20261122) ($100 in USDC).

A from-scratch interpreter for make.fun's tiny stack ISA (`main.ts`, Node 22,
no dependencies): 32-bit wrapping integers, a 256-value stack, calls, 256
words of memory, input/output, and all ten traps with their exact exit codes —
including exact `MUL` (`Math.imul`), unsigned `DIVU`/`MODU`/`LTU`,
`-2147483648 / -1`, 5-bit shift counts, `PUSH8` sign extension, `EXIT`'s low
byte, and the step and output limits.

Practice score: 1,000,000 (40/40 instances at 1,000 points), deterministic.
