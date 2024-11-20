
# Tic Tac Toe - Terminal Game 🎮

A simple two-player Tic Tac Toe game implemented in Java, playable in the terminal. The game alternates turns between two players (`X` and `O`), checks for wins, and detects draws.

## Features ✨
- **Two-Player Mode**: Players take turns entering their moves.
- **Win Detection**: Automatically checks for a winner after each move.
- **Draw Detection**: Declares a draw if all cells are filled without a winner.
- **Input Validation**: Ensures players enter valid moves (within bounds and on empty cells).

## How to Play 🕹️
1. **Run the Program**:
   - Compile: `javac TicTacToe.java`
   - Run: `java TicTacToe`
2. **Input Moves**:
   - Players input their moves by specifying the row and column numbers (e.g., `0 1`).
   - Rows and columns are zero-indexed (0, 1, or 2).
3. **Win or Draw**:
   - The game ends when one player achieves three in a row (horizontal, vertical, or diagonal).
   - If the board is full and no player wins, it's declared a draw.

## Example Gameplay 🎲

```
Welcome to Tic Tac Toe!
| | | |
| | | |
| | | |

Player X, enter your move (row and column: 0 1):
0 1
| |X| |
| | | |
| | | |

Player O, enter your move (row and column: 1 1):
1 1
| |X| |
| |O| |
| | | |

Player X wins!
```

## Prerequisites 🛠️
- **Java Development Kit (JDK)**: Ensure you have JDK 8 or later installed.
- **Terminal**: Any terminal/command prompt.

## Files 📂
- `TicTacToe.java`: The source code for the game.

## To-Do List 📝
- Add an option to restart the game without rerunning the program.
- Implement AI for a single-player mode.
- Add scoring to track multiple rounds.

## Contributing 🤝
Feel free to fork this project and make improvements. Pull requests are welcome!
