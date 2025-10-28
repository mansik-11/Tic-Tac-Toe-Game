# Tic-Tac-Toe Game

A classic, browser-based Tic-Tac-Toe game built with plain HTML, CSS, and JavaScript. This project provides a clean interface for two players to compete against each other.

<img width="1919" height="806" alt="Screenshot 2025-10-28 224440" src="https://github.com/user-attachments/assets/23fba621-5fba-4d40-b0ba-c99a46242975" />


## ✨ Features

*   **Classic Gameplay**: A 3x3 grid where two players (X and O) take turns.
*   **Win Detection**: The game automatically detects and announces when a player wins.
*   **Draw Detection**: The game logic includes a counter to track moves and determine a draw.
*   **Player Turn Indicator**: The game logic switches between 'O' and 'X'.
*   **Responsive Design**: A simple and clean UI that works on different screen sizes.
*   **Reset and New Game**: Players can easily reset the board or start a new game.

## 🛠️ Technologies Used

*   **HTML5**: For the basic structure and content of the game.
*   **CSS3**: For styling the game board, buttons, and messages.
*   **JavaScript (ES6)**: For all the game logic, DOM manipulation, and event handling.

## 🚀 How to Play

1.  Open the `index.html` file in your favorite web browser.
2.  You will see a welcome alert. Click "OK" to start.
3.  Player 'O' always starts the game.
4.  Click on any empty box in the grid to place your mark.
5.  Players take turns until one player gets three of their marks in a row (horizontally, vertically, or diagonally).
6.  The winner is announced at the top of the screen.
7.  If all boxes are filled and no one has won, the game is a draw.
8.  Click the **"New Game"** or **"Reset Game"** button at any time to start over.

## 📂 Project Structure

The project consists of the following files:

```
WD--main/
├── index.html      # The main HTML file with the game board structure
├── style.css       # CSS file for styling the game
├── script.js       # JavaScript file containing the game logic
└── README.md       # This file
```

*   `index.html`: Contains the structure of the game board, buttons, and message container.
*   `style.css`: (Assumed) Contains styles for the layout, colors, and fonts.
*   `script.js`: Handles all the client-side logic:
    *   Setting up the game board.
    *   Handling player clicks.
    *   Switching turns between 'O' and 'X'.
    *   Checking for a winner or a draw.
    *   Resetting the game state.

## 📝 Note on `code.js`

The `code.js` file included in the project contains a list of currency codes mapped to country codes. This file is not used by the Tic-Tac-Toe game and appears to be for a separate currency-related feature or project.

## 📜 License

This project is open-source and available for anyone to use.

---

*Happy Gaming!*
