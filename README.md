# Tic Tac Toe (1D)

A C++ console implementation of the classic Tic Tac Toe game (3x3 grid, 1D array). Play as "X" against the computer ("O") on your terminal. The game checks for wins and ties and is easy to run on Linux, Windows, or macOS.

## Features

- Play as "X" against the computer's "O"
- Board displayed in an easy-to-read format
- Detects wins and ties automatically
- Simple command line interface
- Cross-platform: works on Linux, Windows, and macOS

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/XingChen47/Tic-Tac-Toe-1D.git
cd Tic-Tac-Toe-1D
```

### 2. Compile the program

#### **Linux/macOS**
```sh
g++ -o tictactoe "Tic Tac Toe (1D) .cpp"
```

#### **Windows (using MinGW)**
```sh
g++ -o tictactoe.exe "Tic Tac Toe (1D) .cpp"
```
*Make sure `g++` is available in your PATH.*

## Usage

Run the compiled program from your terminal:

**Linux/macOS:**
```sh
./tictactoe
```

**Windows:**
```sh
tictactoe.exe
```

You will be prompted to enter a position (1-9) for your move. The computer will make a random move after yours. The game ends when someone wins or the board is full (tie).

**Example Output:**
```
WELCOME TO TIC-TAC-TOE!

     |     |     
  X  |     |  
_____|_____|_____
     |     |     
     |  O  |  
_____|_____|_____
     |     |     
     |     |  
_____|_____|_____

Enter a where you wish to place your marker (1-9) 5

...

YOU WIN!
THANKS FOR PLAYING!
```

## Customization

You can tweak the computer's logic, board size, or victory messages by editing the source code.
