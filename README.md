# Game

The code includes two classes: "Words" and "GuessTheWord".

The "Words" class contains an array of words to choose from, selects a random word from that array and initializes an array of letters. It also includes methods to check if all the letters of the selected word have been guessed, to guess a letter and update the letters array accordingly, and to return a string representation of the letters array with hyphens for letters that have not been guessed yet.

The "GuessTheWord" class handles the game logic by showing the current state of the word being guessed, reading the user's guess, checking if the guess is correct and updating the game state accordingly. It also includes methods to start and end the game. The game allows the user to guess a letter and has 10 rounds to correctly guess the word. If the user guesses all the letters correctly within the 10 rounds, the game is won; otherwise, the game is lost.
