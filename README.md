[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/FiluFafayo/tiny-stack-vm-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/FiluFafayo/tiny-stack-vm-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

# tiny-stack-vm-20261122

A faithful interpreter of make.fun's tiny-stack ISA v1, for the [tiny-stack-vm-01-run-20261122](https://make.fun/c/tiny-stack-vm-01-run-20261122) bounty ($100, top 10 × $10).

`main.ts` runs as `node /bot/main.ts`: for each `/input/<id>/` it runs `program.bin` on `input.bin`, writing `/output/<id>/stdout.bin` and `/output/<id>/exit.txt`.

A direct port of the kit's reference VM (`vm.mjs`): same check order, 32-bit wrapping arithmetic, all ten traps with exact exit codes. Practice score 1,000,000.
