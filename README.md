# Connect Four AI Game

This project is a Python-based Connect Four game built with Pygame. 
It includes an AI opponent that uses the Minimax algorithm with Alpha-Beta pruning. 
The game has three difficulty levels (Easy, Medium, Hard) that change how deep the AI searches for the best move.

## Requirements
You need to have the following Python packages installed:
- pygame 
- numpy 

## How to Run
Run the following file in your Python environment:

python Connect4_With_Minimax_Algorithm


## How to Play
1. Choose the AI difficulty level (1 = Easy, 2 = Medium, 3 = Hard) in the console.
2. When the game window opens, click on a column to drop your piece.
3. The AI will automatically make its move after yours.
4. The first player to connect four pieces in a row (horizontal, vertical, or diagonal) wins.
5. Close the window to exit the game.

## Notes
- The AI uses Minimax with Alpha-Beta pruning.
- Difficulty levels correspond to search depths of 2, 4, and 6.
- Works for all win directions and includes proper game-over handling.
- Tested on Python 3.10+ with Pygame 2.x.
