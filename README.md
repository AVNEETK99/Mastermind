# Mastermind

Mastermind is a classic code-breaking board game for two players. One player is the "codemaker" and creates a secret code of four colored pegs, while the other player is the "codebreaker" and tries to guess the code by placing their own colored pegs on the board and receiving feedback on their guesses. The codebreaker has a limited number of attempts to crack the code, and the game continues until either the codebreaker correctly guesses the code, or they run out of attempts.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python mastermind.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The code imports the necessary modules for the program: ```tkinter```, ```random```, and ```tkinter.messagebox```.
* There is a function called ```"check"``` that will determine whether the user's guess is correct or not. It takes in global variables for the answer, the user's guess, and the number of chances the user has left.
* The function initializes a counter called ```cnt to 0```, which will keep track of how many of the user's guesses are correct.
* The function checks if the user still has chances left to make a guess. If there are no more chances left, the function will display the correct answer and end the game.
* The function then checks if the user's guess is correct. If the user has made 0 correct guesses, the "correct" variable is set to 0. If the user has made 1 correct guess, the "correct" variable is set to 1, and so on.
* The function then decrements the number of chances the user has left and returns 0.
* There is a function called ```"startGame"``` that initializes the GUI for the Mastermind game.
* The function creates a window called "wn" with a title, dimensions, and background color.
* The function creates global variables for the number of chances, the correct guesses, and the user's guesses.
* The function generates a random answer for the user to guess.
* The function creates labels and radio buttons for the user to make their guess.
* When the user has made a guess, the function calls the ```"check"``` function to see if the guess is correct.
* If the user has guessed correctly, the game ends and a message box pops up congratulating the user.
* If the user has used up all their chances, the game ends and a message box pops up displaying the correct answer.
