# Hangman Game Project

## Overview

The Hangman Game is a classic word guessing game where the player needs to guess
the letters of a secret word. The player has a limited number of chances (lives)
to guess the correct letters, and with each incorrect guess, a part of a hanging
man is drawn, adding to the suspense. The objective of the game is to guess the
entire word before running out of lives.

## Project Description

In this Hangman project, you will create a text-based implementation of the
Hangman game in Python. The program will randomly select a word from a
predefined word list, display blanks for each letter in the word, and prompt
the user to guess a letter. The game will continue until the player either
correctly guesses the entire word or runs out of lives.

## Features

1. **Random Word Selection:** The program will randomly select a secret word
from a list of predefined words.
2. **Display:** The program will display the current state of the word using
underscores ('_') to represent unguessed letters and revealed letters for
correctly guessed ones.
3. **Guessing:** The user will be prompted to guess a letter, and the program
will check if the letter is in the word.
4. **Incorrect Guesses:** If the guessed letter is not in the word, the program
will deduct a life from the player and display a part of the hangman.
5. **Already Guessed Letters:** The program will inform the user if they have
already guessed a specific letter.
6. **Win/Loss Condition:** The game will terminate and display "You win." if the
player correctly guesses the entire word. If the player runs out of lives before
guessing the word, the game will terminate and display "You lose."

## Required Libraries

The following libraries are required to run the Hangman game:

1. **random:** To select a random word from the word list.
2. **hangman_words:** A custom module that contains the list of words for the game.
3. **hangman_art:** A custom module that contains ASCII art of the hangman stages.

## How to Play

1. Run main.py, and you will see the hangman logo displayed at the
beginning.
2. The program will show the word with underscores representing unguessed letters.
3. Enter a letter as your guess when prompted.
4. If the letter is part of the word, it will be revealed in its correct position.
5. If the letter is not in the word, the program will display a part of the
hangman and deduct a life.
6. Continue guessing letters until you correctly guess the entire word or run out of lives.
7. If you win, the program will display "You win." If you lose, it will display "You lose."

Enjoy playing Hangman!
