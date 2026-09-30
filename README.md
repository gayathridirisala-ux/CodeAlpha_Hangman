# Hangman Game

## Project Overview

This project is a simple text-based Hangman game developed using Python.

The player has to guess a hidden word one letter at a time. The game provides a maximum of 6 incorrect guesses.

## Features

- Contains 5 predefined words
- Selects a random word for each game
- Allows the player to guess one letter at a time
- Tracks guessed letters
- Allows a maximum of 6 incorrect guesses
- Displays whether the player wins or loses
- Console-based input and output

## Technologies Used

- Python
- Random module

## How to Run

1. Make sure Python is installed on your computer.
2. Open the project folder in VS Code.
3. Open `hangman.py`.
4. Run the program.
5. Enter one letter at a time when prompted.

## Game Rules

- Guess the hidden word one letter at a time.
- Correct letters are displayed in their positions.
- Incorrect guesses are counted.
- The player can make a maximum of 6 incorrect guesses.
- The player wins by guessing all the letters before reaching 6 incorrect guesses.

## Sample Output

```text
===== WELCOME TO HANGMAN =====

Word: _ _ _ _ _ _

Guess a letter: p
Correct guess!

Word: p _ _ _ _ _

Congratulations! You guessed the word: python

===== THANK YOU FOR PLAYING =====