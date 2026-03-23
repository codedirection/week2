
# 📘 Assignment: Games in Python

## 🎯 Objective

Build the classic word-guessing game using Python strings, loops, and user input. Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️	Game Setup and Word Selection

#### Description
Set up the game structure and implement random word selection from a predefined list.

#### Requirements
Completed program should:

- Define a list of words for the game
- Randomly select a word from the list
- Initialize game state (hidden word display, attempts remaining)

### 🛠️	Letter Guessing and Progress Tracking

#### Description
Implement the core game loop that accepts letter guesses and updates the game progress.

#### Requirements
Completed program should:

- Accept letter guesses from the user
- Show current progress in _ _ _ format for unguessed letters
- Track incorrect guesses remaining
- Update the display after each guess

### 🛠️	Win/Lose Conditions

#### Description
Add logic to check for win or lose conditions and display appropriate messages.

#### Requirements
Completed program should:

- End the game when the word is fully guessed
- End the game when attempts are exhausted
- Display win/lose messages with the correct word revealed
