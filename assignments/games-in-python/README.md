
# 📘 Assignment: Games in Python

## 🎯 Objective

Build the classic word-guessing game in Python using strings, loops, conditionals, and user input. Students will implement a simplified Hangman-style game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the game scaffold and select a random secret word from a predefined list.

#### Requirements
Completed program should:
- Define a list of words for the game
- Randomly select one word from the list
- Initialize game state variables (`attempts`, `guessed_letters`, `display_word`)

### 🛠️ Letter Guessing and Progress Tracking

#### Description
Implement the main game loop to accept guesses, validate input, and update progress display.

#### Requirements
Completed program should:
- Accept single-letter guesses from the user (case insensitive)
- Show current word progress with unrevealed letters as underscores (e.g., `h _ n g m _ n`)
- Track correct and incorrect guesses separately
- Decrement remaining attempts on wrong guesses

### 🛠️ Win/Lose Conditions

#### Description
Add game completion checks and user feedback for win/lose outcomes.

#### Requirements
Completed program should:
- Detect a win when all letters are guessed
- Detect a loss when attempts run out
- Display final win/lose message and reveal the full secret word

## 📌 Optional Enhancements (stretch goals)

- Allow the user to guess the full word
- Prevent duplicate guess penalties
- Add ASCII art for hangman stages

