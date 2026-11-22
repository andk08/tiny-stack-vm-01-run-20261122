# Tiny Stack VM

![tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)
![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/andk08/tiny-stack-vm-01-run-20261122/rank.svg)
![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/andk08/tiny-stack-vm-01-run-20261122/reward.svg)

A tiny stack virtual machine for make.fun's tiny stack ISA (version 1): 32-bit wrapping integers, a 256-value stack, calls, 256 words of memory, input and output, and ten traps with their own exit codes. Run it with `node main.ts`; it reads `MAKEFUN_INPUT_DIR` (default `/input`) and writes each instance's answer to `MAKEFUN_OUTPUT_DIR` (default `/output`).

Verified before submit: practice 40/40, grade-local 1,000,000 against a 670,000 baseline, and the grader-style reproduction as user `nobody` exits 0 with byte-identical output on a fresh run and a re-run. The repository is 7,718 bytes, under the 8,192-byte cap.
