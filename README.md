# Tic-Tac-Toe Game in Java

This is a simple console-based Tic-Tac-Toe game implemented in Java. The game is designed for two players playing on the same machine in turns, using a 3x3 board.

## 📋 Features

- Two-player game: "X" and "O"
- Turn-based input via console
- Input validation for invalid or occupied cells
- Automatically detects wins, losses, or draws
- Easy-to-read board display in the terminal

## 🧠 How the Game Works

- The board is represented as a 1D array of size 9.
- Each slot is initially numbered from 1 to 9.
- Players take turns to enter the slot number to place their symbol (`X` or `O`).
- The game continues until:
  - A player gets three in a row (horizontal, vertical, or diagonal), or
  - All cells are filled, resulting in a draw.

## ▶️ Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- A terminal or IDE that supports Java

### How to Compile and Run

1. Save the code in a file named `TicTacToe.java`.
2. Open your terminal and navigate to the directory containing the file.
3. Compile the code:
   
   javac TicTacToeava
