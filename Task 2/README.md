
## Overview
This is a simple Tic-Tac-Toe game with an AI opponent implemented using Python's Tkinter library for the graphical user interface (GUI). The AI is designed to play against a human player with various strategies to ensure competitive gameplay.

## Features
- **Graphical User Interface**: The game uses Tkinter for a simple and clean interface.
- **AI Opponent**: The AI can play against a human player with strategies to ensure a challenging game.
- **Reset Functionality**: Allows the game to be reset and played again without restarting the program.
- **Two Modes**: 
  - **Machine vs. Human**: The AI starts first.
  - **Human vs. Machine**: The human player starts first.

## Installation
Ensure you have Python installed on your system. The code uses the Tkinter library, which is included in standard Python installations. No additional libraries are required.

## Usage
1. Save the provided code to a file, e.g., `tic_tac_toe_ai.py`.
2. Run the script using Python:
   ```sh
   python tic_tac_toe_ai.py
   ```

## Code Explanation

### Initialization
The `TIC_TAC_TOE_AI` class initializes the game, sets up the GUI, and prepares the necessary variables to manage the game's state.

### GUI Setup
The `decorating` method sets up the game window, including:
- The title label.
- The 3x3 grid of buttons for the Tic-Tac-Toe board.
- Control buttons to start the game (either as Machine vs. Human or Human vs. Machine) and to reset the game.

### Game Flow
- **reset**: Resets the game state for a new game.
- **control_give**: Sets up the game mode based on who starts first (AI or human).
- **game_over_management**: Disables all buttons and enables the reset button when the game is over.

### AI Logic
- **__machine_play**: Manages the AI's moves based on the current state of the game.
- **__sign_insert**: Inserts the 'X' or 'O' sign into the selected button and updates the game state.
- **machine_line_match** and **human_line_match**: Check if there is a winning line for the machine or human, respectively.

### Human Player
- **__human_play**: Allows the human player to make a move by clicking on a button.

### Helper Methods
Several methods assist in the AI's decision-making, handling different scenarios and strategies based on the current game state.

## Future Improvements
- Implement more sophisticated AI strategies.
- Add a feature to select difficulty levels for the AI.
- Improve the GUI design for better user experience.

## License
This project is open-source and available under the MIT License.

## Contributing
Feel free to submit issues or pull requests if you want to contribute to improving the game.
