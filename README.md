[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/VUXXE/tiny-chess-01-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/VUXXE/tiny-chess-01-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01-engine

A deterministic chess engine in 4 KB of Python 3.13 (standard library only), built for make.fun's [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01) bounty.

## Features
- 10x12 mailbox board with incremental Zobrist hashing and 3-fold repetition detection
- Iterative deepening with PVS, aspiration windows, null-move pruning, late-move reductions, and check extensions
- Quiescence search with delta pruning and MVV-LVA ordering
- Transposition table, killer moves, and history heuristic
- Tapered middlegame/endgame evaluation with piece-square tables, bishop pair, rook open/semi-open files, and pawn structure
