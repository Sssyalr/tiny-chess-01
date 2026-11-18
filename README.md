# tiny-chess-01

A chess engine in 4 KB of Python. 0x88 board, alpha-beta search with
quiescence, transposition table, killer/history move ordering, null-move
pruning, and a tapered midgame/endgame piece-square evaluation. It plays
through the make.fun env (`MAKEFUN_ENV_URL`), searching to a fixed node
budget per move so replays are deterministic.

`main.py` is the compressed entrypoint (see `engine.py`, the readable
source it was packed from with `makefun compress`).
