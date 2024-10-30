

---

# Rock Paper Scissors Game

This Rock Paper Scissors game is a Python-based command-line game where you can play against the computer. The program tracks scores across rounds, providing a fun way to test your luck and strategy.

## Features
- **Interactive Gameplay**: Play Rock Paper Scissors with the computer.
- **Score Tracking**: Keeps track of the user and computer scores across multiple rounds.
- **Round Customization**: Choose the number of rounds for a "best-of" format.
- **Randomized Choices**: The computer's choices are randomly generated.

## Installation
1. Ensure Python (version 3.x) is installed.
2. Download or clone this repository.
3. Run the game script in a terminal or command prompt.

## Usage
1. Run the program:
   ```bash
   python rock_paper_scissors.py
   ```
2. Choose the number of rounds for the match.
3. Enter your choice for each round:
   - **1** for Rock
   - **2** for Paper
   - **3** for Scissors
4. After each round, the current score will display. Once all rounds are completed, the game announces the final winner.

### Example Gameplay
```plaintext
Rock Paper Scissors

Best out of how many rounds? 3

Choices:
1 - Rock
2 - Paper
3 - Scissors

Round 1:
Enter your choice (1, 2, or 3): 1
You choose Rock
Computer chooses Paper
Computer wins this round!
Score: You 0, Computer 1
```

## Code Overview

- **Functions**:
  - `print_options()`: Displays game choices.
  - `get_user_choice()`: Validates and retrieves the user's choice.
  - `get_computer_choice()`: Generates a random choice for the computer.
  - `print_round_result()`: Displays results of each round and updates the score.
  - `print_final_result()`: Announces the final winner based on scores.

- **Gameplay Loop**:
  - The game runs for a user-defined number of rounds, displaying choices and results for each round.

## License
This project is for educational and entertainment purposes. Feel free to modify it and expand upon the game.

---

This README explains the functionality and usage instructions for the Rock Paper Scissors game. Enjoy playing!
