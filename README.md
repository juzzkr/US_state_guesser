# US State Guesser

## Description
The US State Guesser is an interactive quiz that challenges players to name all 50 states in the United States. As users input their guesses, the correct states will be displayed on a map. This project combines fun with education, making it a great tool for learning U.S. geography.

## Key Features
- **Interactive Map**: An engaging visual representation of the U.S. with states to guess.
- **Progress Tracking**: Displays the number of correctly guessed states in real-time.
- **Feedback Mechanism**: Correct guesses are marked on the map, while incorrect ones are simply ignored.
- **Exit Option**: Players can exit at any time, with the option to save unguessed states for later review.
- **Educational Tool**: Helps users learn U.S. geography in a fun and interactive way.

## How to Play
1. **Start the Game**: Launch the game by running the `main.py` script.
2. **Guess the States**: A text input box will appear where you can type the name of a state. The first letter of each state should be capitalized.
3. **Correct Guesses**: If your guess is correct, the state will be displayed on the map.
4. **Continue Guessing**: Keep guessing until you either name all 50 states or choose to exit.
5. **Exit the Game**: If you want to stop playing, type "Exit" in the input box. All unguessed states will be saved in `states_to_learn.csv` for later reference.

## Technologies Used
- **Python**: The programming language used to develop the game.
- **Turtle**: A standard Python library for creating simple graphics and animations.
- **Pandas**: A data manipulation library used to handle state data and save progress.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/US_state_guesser.git
   cd US_state_guesser
   python main.py

