# tiny-chess-01-r12

From-scratch chess engine for the make.fun tiny-chess-01 competition.

- 0x88 board, undo-based make/unmake, incremental evaluation
- alpha-beta + iterative deepening + quiescence, LMR, check extensions
- killer + history move ordering, transposition table
- fixed 30,000-node per-move budget, deterministic (no wall clock)
- `main.py` is an LZMA+base85 packed payload (stdlib only), 4047 bytes
