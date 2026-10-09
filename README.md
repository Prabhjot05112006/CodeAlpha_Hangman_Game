# CodeAlpha Hangman Game

A simple text-based Hangman Game developed in Python as part of the CodeAlpha Python Programming Internship.

## Task Objective

The goal of this project is to create a simple Hangman game where the player guesses a word one letter at a time.

## Features

- Uses a predefined list of 5 words.
- Randomly selects one word for each game.
- Player guesses the word one letter at a time.
- Allows a maximum of 6 incorrect guesses.
- Displays the progress of the hidden word.
- Prevents repeated letter guesses.
- Uses simple console input and output.

## Technologies Used

- Python 3
- `random` module

## Python Concepts Used

- Lists
- Strings
- Sets
- `while` loop
- `if-else` statements
- `for` loop
- User input
- Random selection

## How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

### 2. Open the project folder

Open the `CodeAlpha_Hangman_Game` folder in VS Code or another Python editor.

### 3. Run the program

Open the terminal and type:

```bash
python main.py
```

## How the Game Works

1. The program selects a random word from the predefined word list.
2. The word is displayed as underscores.
3. The player enters one letter.
4. If the letter is correct, it is revealed in the word.
5. If the letter is incorrect, the incorrect guess count increases.
6. The player can make up to 6 incorrect guesses.
7. The player wins when all letters of the word are guessed.
8. The game ends when the word is guessed or 6 incorrect guesses are reached.

## Example

```text
================================
       HANGMAN GAME
================================
Guess the word one letter at a time.
You have 6 incorrect guesses.

Word: _ _ _ _ _ _
Incorrect guesses: 0
Enter a letter: p

Correct guess!

Word: p _ _ _ _ _
```

## Project Structure

```text
CodeAlpha_Hangman_Game/
│
├── main.py
└── README.md
```

## Internship

**Company:** CodeAlpha  
**Domain:** Python Programming  
**Task:** Task 1 — Hangman Game

This project was created as part of the CodeAlpha Python Programming Internship.
