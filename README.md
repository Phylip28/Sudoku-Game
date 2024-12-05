# Sudoku Game in Python

## Description
This is a **Sudoku** game developed in Python. The goal of the game is to complete the 9x9 grid with numbers from 1 to 9, ensuring that no number repeats in any row, column, or 3x3 block. The game generates an initial board with some numbers already placed, and the player can fill in the empty cells.

## Features
- **Interactive Board:** Players can select empty cells and input numbers from 1 to 9.
- **Rule Verification:** The game checks that the Sudoku rules are followed (no repeating numbers in rows, columns, or 3x3 blocks).
- **Game Instructions:** The game provides detailed instructions on how to play and how to interact with the board.

## How to Play

1. **Start a Game:** The player can start a new game from the main menu.
2. **How to Play:** Provides instructions on the game rules and player interactions.
3. **Exit the Game:** The player can quit the game at any time.

### Input Format
The player must input the coordinates of the cell they wish to modify in **letter-number** format (e.g., **A1**, **B2**, etc.). Then, they must input a number between 1 and 9 to fill in the selected cell.

### Rules
- Each row must contain the numbers from 1 to 9 without repetition.
- Each column must contain the numbers from 1 to 9 without repetition.
- Each 3x3 block must contain the numbers from 1 to 9 without repetition.

## Installation

To play this game, make sure you have **Python 3.x** installed on your system. If you don't have it, you can download it from the official [Python website](https://www.python.org/downloads/).

1. Clone this repository:
    ```bash
    git clone https://github.com/Phylip28/Sudoku-Game.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Sudoku-Game
    ```

3. Run the game:
    ```bash
    python sudoku.py
    ```

## Credits
This project was developed by [Phylip28](https://github.com/Phylip28). If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
