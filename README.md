# AI Tic-Tac-Toe with Minimax

A simple Tic-Tac-Toe game built in Python where you play against an AI opponent. The AI uses the Minimax algorithm to analyze possible moves and choose the best one, making it a fun way to explore how decision-making works in artificial intelligence.

## About the Project

This project was created to understand the basics of AI in games and how algorithms can be used to make intelligent decisions. Instead of making random moves, the AI evaluates different game scenarios and selects the move that gives it the highest chance of winning.

The game features a graphical user interface built with Tkinter, allowing players to interact with the board easily.

## Features

* Play Tic-Tac-Toe against an AI opponent
* AI powered by the Minimax algorithm
* Interactive and user-friendly GUI using Tkinter
* Automatic detection of wins, losses, and draws
* Restart option to play multiple games
* Demonstrates basic concepts of game AI and search algorithms

## Technologies Used

* Python
* Tkinter
* Minimax Algorithm
* Recursion

## How the AI Makes Decisions

The AI uses the Minimax algorithm, a popular strategy used in turn-based games. It explores all possible future moves and evaluates the outcome of each scenario before making a decision.

In simple terms, the AI:

1. Looks at every possible move.
2. Predicts how the player might respond.
3. Evaluates future game states.
4. Chooses the move that leads to the best possible outcome.

Because the algorithm always chooses the optimal move, beating the AI is extremely difficult.

## Project Structure

```text
AI_Project/
│
├── tic_tac_toe.py
├── README.md
```

## Running the Project

### Clone the repository

```bash

```

### Navigate to the project folder

```bash
cd AI_Project
```

### Run the game

```bash
python tic_tac_toe.py
```

## Game Rules

* You play as **X**
* The AI plays as **O**
* Match three symbols in a row, column, or diagonal to win
* If the board fills up without a winner, the game ends in a draw

## What I Learned

Building this project helped me gain hands-on experience with:

* Artificial Intelligence fundamentals
* Game tree search techniques
* Recursive programming
* Decision-making algorithms
* GUI development using Tkinter

## Future Improvements

Some features that could be added in future versions:

* Multiple difficulty levels
* Alpha-Beta Pruning for faster decision making
* Score tracking system
* Improved UI design
* Sound effects and animations
* Online multiplayer support

## Author

**Vishal Sharma**

## License

This project was developed for educational and learning purposes.
