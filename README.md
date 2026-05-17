# OldFMchess-js
## Features

### Version 1.0
- Rewrote move generation for a major speed improvement
- Pure material evaluation
- Null-move + Razoring + LMR in main search
- Hash table
- Mobility evaluation (thanks to Fruit)
- Bishop pair bonus
- Repetition draw detection
- Improved null-move pruning (thanks to Stockfish)
- Improved LMR (again, thanks to Stockfish)
- Various speed optimizations
- Killer moves
- Tuned PSQ tables / mobility
- Better king evaluation in endgames (king no longer stays on the back rank)
- Displays '#' for checkmate
- Improved UI (new game, switch black/white, choose move time)
- Other minor bug fixes
- Speed optimizations
- SEE added (QSearch pruning, removes losing captures in main search)
- No null-move in pawn endgames
- Added position analysis support for supported browsers
- Added support for pasting FEN positions
- Added checks in first ply q-search (+15)
- Bonus for knights attacking pawns (+20)
- Bonus for bishop pins (+40)

### Version 1.1
- Added tapered evaluation
- Added pawn structure evaluation (thanks again to Stockfish)
- Added 2 strength levels
- Redesigned UI (modern look, friendly/challenge mode, warnings when changing modes, levels, and starting new games)
- Fixed bug when using hash moves
- Fixed crashes caused by invalid hash moves
- Other minor bug fixes
- Fixed hashtable bug (previous RNG was poor)
- Fixed starting position when playing black
- Improved hashtable storage (does not increase ELO much, but greatly helps in endgames)
