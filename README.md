

---

# Number Guessing Game

A simple command-line number guessing game written in Python. The program generates a random secret number between 1 and 1000, and the player has 10 attempts to guess it correctly.

## Features

* Randomly selects a secret number between 1 and 1000.
* Validates user input to ensure guesses are within the specified range.
* Provides feedback if the guess is too high or too low.
* Limits the number of attempts to 10.
* Congratulates the player if they guess correctly within the attempts.
* Reveals the secret number if the player runs out of attempts.

## How to Play

1. Run the program.
2. Enter your guess when prompted.
3. Receive feedback if your guess is too high, too low, or correct.
4. Continue guessing until you either guess correctly or run out of attempts.

## Requirements

* Python 3.x

## How to Run

Clone the repository and run the Python script:

```bash
python guessing_game.py
```

Replace `guessing_game.py` with the actual filename if different.

## Example

```
Welcome to the Number Guessing Game!
Guess a number between 1 and 1000: 500
Too low. Try again!
Guess a number between 1 and 1000: 750
Too high. Try again!
...
Congratulations! You guessed the secret number 678 in 5 attempts.

---

