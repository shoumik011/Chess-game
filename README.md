# Chess Game

## Description
This project implements a chess game using Python and Pygame. It allows two players to play against each other on a graphical interface.

## Features
- The game follows standard chess rules, including pawn promotion, castling, en passant, and checkmate/stalemate detection.
- Graphics are implemented using Pygame library, providing a visual representation of the chessboard and pieces.
- Player moves are handled through mouse clicks, with the ability to undo moves.

## Files
- `ChessEngine.py`: Contains the main game logic, including the `GameState` class representing the current state of the game and the `Move` class representing a move.
- `main.py`: The main driver file responsible for handling user input and displaying the game interface.
- `images/`: Directory containing images of chess pieces used for graphics.

## Usage
1. Run `main.py` to start the game.
2. Click on a piece to select it, then click on a valid square to move the piece.
3. The game will handle checkmate, stalemate, and other game outcomes automatically.

## Installation
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd chess-game`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the game: `python main.py`

## Requirements
- Python 3.x
- Pygame library

## Credits
This project was developed by Shoumik Ahmed.



