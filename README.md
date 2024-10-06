# Rock, Paper, Scissors Game

This project is a simple command-line game of **Rock, Paper, Scissors** implemented in Java. The user plays against the computer, and the winner is determined based on the rules of the classic game. This project showcases basic programming concepts such as user input, random number generation, and conditional logic.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Rules of the Game](#rules-of-the-game)
- [How It Works](#how-it-works)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Overview

The Rock, Paper, Scissors game is a fun way to demonstrate basic programming constructs like conditional statements and user interaction. The program asks the user to choose between Rock, Paper, or Scissors, and the computer makes a random choice. The winner is then determined based on the game's rules.

## Features

- Simple, text-based interface that runs in the terminal.
- User chooses between Rock, Paper, or Scissors by entering a number (1, 2, or 3).
- The computer makes a random choice.
- The program displays both the user’s and the computer’s choices.
- The winner is announced based on the rules of Rock, Paper, Scissors.
- Handles invalid inputs gracefully.

## Setup

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- A Java IDE or command-line environment for compiling and running Java programs.

### Installation

1. Clone the repository or download the source code.
2. Compile the `RPSGame.java` file:
   ```bash
   javac RPSGame.java
   ```
3. Run the compiled program:
   ```bash
   java RPSGame
   ```

## Usage

1. When the program starts, it displays a welcome message and instructions for how to play the game.
2. The user is prompted to enter a number:
   - **1**: Rock
   - **2**: Paper
   - **3**: Scissors
3. The computer randomly selects one of these three options.
4. The program announces both the user’s and the computer’s choices and determines the winner based on the following rules:
   - Rock beats Scissors.
   - Scissors beats Paper.
   - Paper beats Rock.
5. The result (win, lose, or tie) is displayed on the screen.

   ### Example Output

   ```
   Welcome everyone! We are so glad you are here! Enter 1, 2, or 3. Pick only one number! 1 is Rock, 2 is Paper, 3 is Scissor 2 User chose Paper Computer chose Scissors. Scissors beats paper, Player loses!
   ```

## Rules of the Game

- **Rock** beats **Scissors**.
- **Scissors** beats **Paper**.
- **Paper** beats **Rock**.
- If both the user and the computer make the same choice, the game is a tie.

## How It Works

The program consists of the following parts:

- **`main()` Method**: Initializes the game, displays instructions, and prompts the user to enter a choice. It then calls the `playGame()` method to determine the winner.
- **`playGame(int choice, int computerChoice)` Method**:
  - Prints out the user's and computer's choices.
  - Determines the winner based on the rules above and displays the result.

The computer's choice is generated using `Math.random()` to simulate randomness. User input is collected using the `Scanner` class.

## Future Enhancements

Possible improvements to this project include:

- **Implementing a best-of-three or best-of-five game mode**.
- **Adding more options** like "Lizard" and "Spock" to extend the game's rules.
- **Tracking and displaying the player's win/loss record**.
- **Improving user input validation** to handle invalid entries more effectively.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

Jai Vang
# RPA_Game
