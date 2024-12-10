
# XO-AI

XO-AI is a dynamic Tic Tac Toe game where players can compete against an intelligent AI opponent. Built with Python and Tkinter, the game features an unbeatable AI powered by the Minimax algorithm, ensuring optimal moves and strategic decision-making. The project provides a clean interface, seamless gameplay, and a scoring system to keep track of wins, losses, and ties.


## Features

-   **Unbeatable AI Logic**: The AI uses the Minimax algorithm to calculate the best possible move, making it challenging for players to win.
-   **Dynamic Interface**: Built with Tkinter, the game has a simple and responsive user interface.
-   **Human vs AI Gameplay**: Play as 'X' while the AI competes as 'O'.
-   **Turn Delay**: AI moves are delayed for a natural and realistic gameplay experience.
-   **Score Tracking**: Track your wins, losses, and ties with an in-game scoreboard.
-   **Replay Functionality**: Easily restart the game and alternate who plays first.



## Requirements

To run XO-AI, ensure you have the following:

-   Python 3.7 or higher
-   Required libraries: `numpy`, `tkinter` (built into Python)

Install the required dependencies using:

```bash
pip install numpy tkinter
```


## How to Run

1.  Clone this repository:
    
    ```bash
    git clone git@github.com:rajatmaheshwari17/XO-AI.git
    ```
    
2.  Navigate to the project directory:
    
    ```bash
    cd XO-AI
    ```
    
3.  Run the game:
    
    ```bash
    python game.py
    ```
    
## Gameplay

-   **Human Turn**: Click on any grid cell to place your mark ('X').
-   **AI Turn**: The AI calculates and plays its optimal move with a slight delay.
-   **Gameover**: A message announces the winner or if the game ends in a tie.
-   **Play Again**: Click "Click to play again" to restart the game. The first turn alternates between the human and AI.


## Project Structure

-   **`game.py`**: Contains the complete implementation of the game, including AI logic, game mechanics, and user interface.

#
_This README is a part of the XO-AI Project by Rajat Maheshwari._
