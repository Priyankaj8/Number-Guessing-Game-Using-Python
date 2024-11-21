# Number Guessing Game

A fun and interactive **Number Guessing Game** built in Python, where players can either guess a number chosen by the computer or have the computer guess their number based on feedback.

## Features
- **Player vs Computer:** The player guesses a random number selected by the computer.
- **Computer vs Player:** The computer intelligently guesses the player's number based on feedback (*Too High*, *Too Low*, or *Correct*).
- Interactive and console-based gameplay.

## How It Works

### Player Guessing
1. The computer selects a random number within a specified range.
2. The player makes guesses, and the game provides feedback:
   - *"Too High"* if the guess is greater than the target number.
   - *"Too Low"* if the guess is less than the target number.
3. The game ends when the player guesses the correct number.

### Computer Guessing
1. The player thinks of a number within a specified range.
2. The computer makes guesses, and the player provides feedback:
   - *"H"* for "Too High."
   - *"L"* for "Too Low."
   - *"C"* for "Correct."
3. The game ends when the computer correctly guesses the player's number.

## Getting Started

### Prerequisites
- Python 3.x installed on your system.
