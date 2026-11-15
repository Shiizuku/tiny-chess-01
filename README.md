[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Shiizuku/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Shiizuku/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01

A chess engine in 4 KB of Python: `main.py` (4,087 bytes) is the whole
engine. Alpha-beta search with PVS, a transposition table, null-move
pruning, late-move reductions, check extensions and quiescence over
captures, promotions and check evasions, under a fixed 100,000-node
budget (never a clock, so every move is reproducible). Evaluation is
material plus piece-square tables. It plays the make.fun tiny-chess-01
gauntlet through the env at MAKEFUN_ENV_URL.

Entry for make.fun account @qyxra. MIT licensed.
