# Python-Project-2
Tic Tac Toe Application
This is a simple Tic Tac Toe game built using the Tkinter library in Python. It features a graphical user interface where users can play the classic game of Tic Tac Toe.

Requirements:
Python 3.x

Tkinter (usually comes pre-installed with Python)

Pillow library for image handling

Install the Pillow library using pip if you don't have it:

bash
pip install pillow
Usage:
Clone the repository or download the source code.

Ensure you have the required dependencies installed.

Run the tic_tac_toe.py file to start the application.

Structure:
TicTacToe: The main class that initializes the Tic Tac Toe application, manages the GUI, and handles user interactions.

Features:
User-friendly interface to play Tic Tac Toe.

Background image and custom styling.

Players take turns to place their marks on the grid.

Displays the winner or if the game is a tie.

Reset button to start a new game.

Code Overview:
The main components of the application are as follows:

Initialization: Sets up the main window, initializes variables, and calls methods to create the GUI.

create_background: Sets up the background image for the game.

create_title: Creates and displays the game title.

create_buttons: Creates the buttons for the Tic Tac Toe grid.

create_reset_button: Creates the reset button to restart the game.

click: Handles the button click events and checks for the winner or tie.

check_winner: Checks the current state of the grid to determine the winner or tie.

Running the Application:
To run the application, execute the following command in your terminal:

bash
python tic_tac_toe.py
Make sure you have the tic-tac-toe-7737546_1280.png image file in the same directory as the script, as it is used for the background.

reset: Resets the game to its initial state.
