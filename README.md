# Minesweeper

This project implements the classic Minesweeper game along with an AI player capable of making informed moves based on logical deductions. The project consists of two main files:

- `runner.py`: Contains the code to run the graphical interface for playing the game.
- `minesweeper.py`: Contains all the logic for the Minesweeper game and the AI player.

## Classes

### 1. Minesweeper
Handles the gameplay of Minesweeper. It has methods to initialize the game, reveal cells, flag mines, and check for game completion.

### 2. Sentence
Represents a logical sentence in the game, containing a set of cells and a count of how many of those cells are mines. It provides methods to determine known mines and safes, and to update the sentence with new information.

### 3. MinesweeperAI
Implements an AI player that can play Minesweeper intelligently. It keeps track of moves made, known mines, known safes, and logical sentences inferred during gameplay. The AI can mark cells as mines or safes and make moves based on available knowledge.

## Functions to Implement

1. **`add_knowledge()`**:
   - Updates the AI's knowledge based on the current state of the game.
   - Infers new logical sentences from revealed cells and updates existing sentences accordingly.

2. **`make_safe_move()`**:
   - Returns a safe move for the AI to make.
   - A safe move is a cell known not to be a mine.

3. **`make_random_move()`**:
   - Returns a random move for the AI to make.
   - Used when no safe moves are available.

## How to Play

- Run `python runner.py` to play Minesweeper or let the AI play for you.
- The AI makes informed moves based on available knowledge and logical deductions.
- Enjoy playing Minesweeper and see if you can outsmart the AI!

## Notes
- Minesweeper is a classic game that requires both luck and strategy to win.
- The AI is designed to make logical deductions and minimize risk while playing.
- Have fun exploring the game and experimenting with different strategies!

## Acknowledgments
This project is part of a programming assignment or tutorial. It's based on the requirements provided by the instructor or documentation.
