# Number Guessing Game

## Overview
This Python script is an interactive Number Guessing Game where the player guesses a randomly chosen number between 1 and 100. The game offers two levels of difficulty and provides hints to the player based on their guesses.

## Features
- **Random Number Generation**: A number between 1 and 100 is randomly chosen as the target for each game.
- **Difficulty Levels**: Players can choose between 'easy' and 'hard' difficulty levels, which affect the number of guesses allowed.
- **Guess Evaluation**: The game informs the player if their guess is too high, too low, or correct.
- **Interactive Gameplay**: The player inputs their guesses and receives immediate feedback.

## How to Play
1. Run the script to start the game.
2. The game will prompt you to choose a difficulty level ('easy' or 'hard').
3. The game then informs you of the number of guesses you have.
4. Enter your guess for the number.
5. The game will tell you if your guess is too high, too low, or correct.
6. Continue guessing until you find the correct number or run out of turns.

## Functions
- `check_answer(guess, answer, turns)`: Compares the player's guess with the answer and returns the number of turns left.
- `set_difficulty()`: Sets the difficulty level of the game and returns the number of allowed turns.
- `game()`: The main function that runs the game loop, including number generation and taking user input.

## Dependencies
- `random`: Used for generating a random number.
- `art`: This module provides the `logo` which is displayed at the beginning of the game.

## How to Run
Make sure Python is installed on your machine.


## Note
This game is a fun, interactive way to test your number-guessing skills. It's suitable for players of all ages.

---

Enjoy playing, and may your guesses be accurate!