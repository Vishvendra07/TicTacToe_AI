# Tic Tac Toe AI

This project implements an AI-powered Tic Tac Toe game. It allows players to compete against a computer opponent with intelligent decision-making capabilities.

## Features

- **Player vs. AI**: Play Tic Tac Toe against an AI opponent.
- **Minimax Algorithm**: The AI uses the minimax algorithm to make optimal moves.
- **Interactive Gameplay**: User-friendly interface for an engaging experience.

## File Structure

```
.
├── README.md         # Documentation (this file)
├── runner.py         # Main script to run the game
├── tictactoe.py      # Core game logic and AI implementation
```

## How to Play

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vishvendra07/TicTacToe_AI.git
   cd TicTacToe_AI
   ```

2. **Run the Game**:
   Execute the `runner.py` file to start the game:
   ```bash
   python runner.py
   ```

3. **Gameplay**:
   - The game will prompt you to make your move by selecting a position on the grid.
   - The AI will respond with its move.
   - The game ends when either player wins or the grid is full (draw).

## AI Logic

- **Minimax Algorithm**: The AI determines the optimal move by exploring all possible game states and selecting the one that minimizes its potential loss.
- **Heuristic Evaluation**: The algorithm evaluates the board state to determine the best move.

## Prerequisites

- Python 3.x

## Installation

1. **Install Dependencies**:
   This project does not require additional dependencies apart from Python's standard library.

2. **Run the Game**:
   Ensure Python is installed and run the `runner.py` script as described above.

## Future Enhancements

- Add a graphical user interface (GUI) for improved interactivity.
- Allow two-player mode.
- Add difficulty levels for the AI.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.


---

Enjoy playing Tic Tac Toe with an intelligent AI opponent!
