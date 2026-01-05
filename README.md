# HangmanProject
Hangman is a classic word guessing game where a player tries to guess a hidden word by suggesting letters. 

To start, the player is given a word where all letters are replaced with underscores (_) so the only information available is the number of letters in the answer.

Each round the player guesses a letter and if the letter guesed is in the answer, its position (or positions) in the word is revealed. Once they successfully fill in the hidden word with its correct letters, the player wins!

If the letter guessed is not in the answer, the player accumulates mistakes. If they make it to six mistakes without finding the answer, the player loses!

###Your task today is to use python to create a version of this game that you can play inside this python notebook. You may challenge yourself to build it on your own, or you can follow the step by step instructions below.

###Here you can see a simulation of what a few rounds of the game should look like:

The hidden word is: _ _ _ _ _ _

Pick a letter:
E
Correct! There is a letter E in the secret word!

==============================================================

The hidden word is: _ E _ _ E _
Pick a letter:
V
WRONG! Number of mistakes left: 5

    ____________
     |
     O
==============================================================

The hidden word is: _ E _ _ E _
Pick a letter:
L

WRONG! Number of mistakes left: 4

    ____________
     |
     O
    /    
