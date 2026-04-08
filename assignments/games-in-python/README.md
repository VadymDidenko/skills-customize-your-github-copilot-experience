
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a complete Hangman game in Python. You will practice working with strings, loops, conditionals, and user input to create an interactive game experience.

## 📝 Tasks

### 🛠️ Build the Core Hangman Game

#### Description
Create the main game logic for Hangman. Your program should select a random word, display progress to the player, and continue asking for guesses until the game ends.

#### Requirements
Completed program should:

- Store at least 5 possible words in a predefined list.
- Randomly select one word at the start of each game.
- Display the hidden word using underscores separated by spaces (example: `_ _ _ _ _`).
- Ask the user to guess one letter at a time.
- Reveal correctly guessed letters in all matching positions.
- Decrease remaining attempts only for incorrect guesses.

Example progress output:

```text
Word: _ _ _ _ _
Guess a letter: a
Word: _ a _ _ a
Attempts remaining: 5
```

### 🛠️ Handle Win and Lose Outcomes

#### Description
Add end-of-game checks and user feedback so the game clearly finishes with either a win or a loss.

#### Requirements
Completed program should:

- End with a win message when the full word is guessed.
- End with a lose message when attempts reach 0.
- Show the correct word when the player loses.
- Ignore repeated guesses without subtracting an attempt.
- Validate input so only a single alphabetic character is accepted.

Example end-game output:

```text
Congratulations! You guessed the word: banana
```

```text
Game over! The correct word was: banana
```
