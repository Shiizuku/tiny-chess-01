# tiny-chess-01

A chess engine in 4 KB of Python: `main.py` (4,087 bytes) is the whole
engine. Alpha-beta search with PVS, a transposition table, null-move
pruning, late-move reductions, check extensions and quiescence over
captures, promotions and check evasions, under a fixed 100,000-node
budget (never a clock, so every move is reproducible). Evaluation is
material plus piece-square tables. It plays the make.fun tiny-chess-01
gauntlet through the env at MAKEFUN_ENV_URL.

Entry for make.fun account @qyxra. MIT licensed.
