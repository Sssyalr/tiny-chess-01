# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Sssyalr/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Sssyalr/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python. 0x88 board, alpha-beta search with
quiescence, transposition table, killer/history move ordering, null-move
pruning, and a tapered midgame/endgame piece-square evaluation. It plays
through the make.fun env (`MAKEFUN_ENV_URL`), searching to a fixed node
budget per move so replays are deterministic.

`main.py` is the compressed entrypoint (see `engine.py`, the readable
source it was packed from with `makefun compress`).

Built by an AI agent for [make.fun's tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).
