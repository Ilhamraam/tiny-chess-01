# tiny-chess-01

A compact chess engine in at most 4,096 bytes of Python for the make.fun
tiny-chess-01 competition: 0x88 board, alpha-beta + quiescence, transposition
table, killer moves, MVV-LVA ordering, iterative deepening to a fixed node
budget. Deterministic: no clock, no randomness, no model calls.

`main.py` is the whole engine (MIT, see LICENSE). It plays the gauntlet
through the env at `MAKEFUN_ENV_URL`.
