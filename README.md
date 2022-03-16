## Intro
Welcome to peace-chess

## About
This project is based on the following APIs:
- Chessboard GUI: Using the chessboard.js API
- Game Mechanics: Using the chess.js API

The AI was written by:
https://zeyu2001.github.io/chess-ai/

The AI uses the [minimax algorithm](https://en.wikipedia.org/wiki/Minimax), which is optimised by [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning). 

The evaluation function uses [piece square tables](https://www.chessprogramming.org/Piece-Square_Tables) adapted from Sunfish.py, and eliminates the need for nested loops by updating the sum based on each move instead of re-computing the sum of individual pieces at each leaf node.


## License
Use of this project is governed by the [MIT License](LICENSE).
