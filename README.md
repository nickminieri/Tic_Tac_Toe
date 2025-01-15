# Tic-Tac-Clemson

## Overview
**Tic-Tac-Clemson** is a simple command-line implementation of Tic-Tac-Toe, where a human player (Player 1) competes against the computer (Player 2). The game includes random computer moves, win and draw detection, and input validation, ensuring a fair and fun experience.

## Features
- **Interactive Gameplay**:
  - Players select a square (1-9) to place their marker ('C' for Player 1, 'U' for Player 2).
  - The computer makes random valid moves.

- **Game Mechanics**:
  - Win detection (three in a row, column, or diagonal).
  - Draw detection (when all squares are filled without a winner).

- **Replay and Exit Options**:
  - Players can choose to replay or exit the game after each round.
  - Quit the game anytime by entering 'q' or 'Q' when prompted for a move.

- **Robust Input Validation**:
  - Ensures user inputs valid square numbers (1-9).
  - Prevents choosing already occupied squares.

## How to Use
### Compilation
1. Ensure you have a C compiler (e.g., GCC) installed.
2. Compile the program using the following command:
   ```bash
   gcc -o tic_tac_clemson tic_tac_clemson.c -Wall -g -lm
   ```

### Running the Program
1. Run the compiled program:
   ```bash
   ./tic_tac_clemson
   ```
2. Follow the on-screen prompts to:
   - Select your moves (1-9).
   - View the updated board after each turn.
   - Determine the winner or if the game ends in a draw.

### Example Execution
#### Start:
```
Do you want to play a game? (Y/N) Y
Great! Let's play! Welcome to the Game of Tic-Tac-Toe!

Tic-Tac-Clemson:
Player 1 (C) - Player 2 (U)
 --- --- ---
|   |   |   |
 --- --- ---
|   |   |   |
 --- --- ---
|   |   |   |
 --- --- ---

Player 1's turn (C). Enter a number: 5
```

#### After Player 1 Move:
```
Tic-Tac-Clemson:
Player 1 (C) - Player 2 (U)
 --- --- ---
|   |   |   |
 --- --- ---
|   | C |   |
 --- --- ---
|   |   |   |
 --- --- ---

Player 2's turn (U).
```

#### After Computer Move:
```
Tic-Tac-Clemson:
Player 1 (C) - Player 2 (U)
 --- --- ---
|   |   |   |
 --- --- ---
|   | C |   |
 --- --- ---
|   | U |   |
 --- --- ---
```

## Development Notes
- Code written in Visual Studio Code.
- Tested and compiled using GCC without errors or warnings.
- Validated for robust input handling and gameplay mechanics.

## Author
Nicholas Minieri
