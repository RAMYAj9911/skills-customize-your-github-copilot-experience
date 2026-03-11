
# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic word‑guessing Hangman game using Python. This project reinforces string manipulation, loops, conditionals, and user input handling.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the foundation for the Hangman game by defining a list of possible words and selecting one at random at the start of each round.

#### Requirements
Completed program should:

- Define a predefined list of words in the code (minimum 5 words).
- Randomly select one word from that list when the game begins.
- Initialize variables to track correctly guessed letters and remaining attempts.


### 🛠️ Gameplay Loop and Win/Loss Conditions

#### Description
Implement the main loop that accepts user guesses, updates game state, and checks for win or loss conditions.

#### Requirements
Completed program should:

- Prompt the player to guess a single letter at a time.
- Display the current progress of the word using underscores for unknown letters (e.g., `_ a _ g _ a _`).
- Keep track of letters that have already been guessed and prevent duplicate input.
- Deduct an attempt for each incorrect guess and show the number of attempts remaining.
- End the game with a congratulatory message if the word is fully revealed or a losing message when attempts are exhausted.
- Optionally, allow the player to play again or quit after a round ends.


> ⚠️ **Note:** Keep the user interface simple (text‑based) so that students can focus on the logic rather than graphics.

