# python-number-guessing-game
# Number Guessing Game

Simple Python game where user guesses a number.

## Tools
Python

## How to run
Run python number_guessing_game.py

import random

number = random.randint(1, 50)
guess = None

while guess != number:
    guess = int(input("Guess a number between 1 and 50: "))

    if guess < number:
        print("Too low!")
    elif guess > number:
        print("Too high!")
    else:
        print("Correct! You win.")
