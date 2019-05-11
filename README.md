# Phrase Hunter
---

Create a word guessing game: "Phrase Hunter." You’ll use Python and OOP (Object-Oriented Programming) approaches to select a phrase at random, hidden from the player. A player tries to guess the phrase by inputting individual characters.

Flow of the game

Using Python, you’ll create two Python classes with specific attributes and methods. You'll create a Game class for managing the game, and a Phrase class to help with storing attributes of a phrase with specific methods to help determine how to display the phrase in the game.

Your code will choose a random phrase and use some logic you will implement to display each letter of the phrase as underscore character placeholders, _.

Each time the player guesses a letter, the program compares the letter the player has chosen with the random phrase. If the letter is in the phrase, the phrase object is updated so that it displays the chosen letters on the screen.

A player continues to select letters until they guess the phrase (and win), or make five incorrect guesses (and lose).

If the player completes the phrase before they run out of guesses, a winning screen appears. If the player guesses incorrectly five times, a losing screen appears.

A player can guess a letter only once. After they’ve guessed a letter, your programming logic will need to prevent that letter from being guessed a 2nd time.

After building this project, you'll have another great portfolio piece to show off your skills, a fun app that you can share with your friends and family, and a good understanding of the principles of Object-Oriented Programming.


# Project Requirements
---

## Meet Expectations

* The script should not crash due to uncaught exceptions. Raised exceptions should be handled appropriately so the program can continue or exit without a crash
* Instance creation, method calls, print statements, or any calculated execution logic should be wrapped inside a Dunder Main statement for the entry point script of app.py
* The initializer method def __init__ was implemented
* A parameter was defined on def __init__ to allow a single string character argument to be passed in and stored as an instance attribute on the Character object
* The initializer method def __init__ was implemented
* A parameter was defined on def __init__ to allow a phrase argument to be passed in and stored as an instance attribute
* The phrase is composed of a collection of Character object instances
* Includes an initializer that will set a phrases instance attribute to a List of five Phrase objects
* Initializes an instance attribute to store and track the players turns/lives which should start at 5
* Initializes an instance attribute to store the "active phrase", or the phrase the will be guessed by the player
* The entry point script was named properly as: app.py
* Running app.py creates a Game instance and calls an instance method that handles starts the game.

### Prior to the player's first attempt at guessing:

* The phrase should be outputted to the screen showing only _ character placeholders for each character with noticeable spacing between each character.
* One or more plays of a game used strictly Object-Oriented approaches meaning Instance creation and method calls for the entire length of one or multiple plays of the game.

### When a correct character guess is made by the player:

* The phrase is updated on the screen so that all occurrences of the correctly guessed character in the phrase are shown to the player
* The remaining unguessed characters are still hidden as _ characters

### When an incorrectly guessed character is made by the player:

* The player loses a turn/life up to 5 turns/lives
* The player is shown how many turns/lives are remaining

### When a player guesses ALL characters in the phrase:

* The player was shown a winning message
* No more prompts for guesses occur

### When a player runs out of turns/lives before guessing all the of the phrase:

* The player was shown a: "Game over" losing the message
* No more prompts for a guess should occur after the game ends


## Exceeds Expectations

### When a correct character guess is made by the player:

* Validate the player's guess by ensuring the guess is 1 character in length and that it is only letter character: a through z (uppercase or lowercase)
* Any errors/exceptions should be handled

### When an incorrectly guessed character is made by the player:

* Validate the player's guess by ensuring the guess is 1 character in length and that it is only letters: a through z (uppercase or lowercase)
* Any errors/exceptions should be handled

### After winning, the player was prompted to play again:

* if they agree a new game instance should be created OR the current game instance should have its attributes reset to a NEW game state
* if they disagree, the game should end with a message

### After losing, the player was prompted to play again:

* if they agree a new game instance should be created OR the current game instance should have its attributes reset to a NEW game state
* if they disagree, the game should end with a message


