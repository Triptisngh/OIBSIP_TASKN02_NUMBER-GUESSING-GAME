# OIBSIP_TASKN02_NUMBER-GUESSING-GAME
1) The program starts by generating a random number between 1 and 100 using the Math.random() method.

2) The variable attempts is set to 7, representing the number of attempts the user has to guess the correct number.

3) A Scanner object is created to read user input.

4)The program displays a welcome message and informs the user about the range of the number and the number of attempts they have.

5)The game enters a loop that continues until the user guesses the correct number or runs out of attempts. Within the loop:

6)The user is prompted to enter their guess.

7)The program compares the guess with the randomly generated number.

8)If the guess is correct, a victory message is displayed, the celebrateVictory() method is called, and the loop is exited.

9)If the guess is too high or too low, the program provides a corresponding hint.

10)The number of remaining attempts is decremented, and the updated count is displayed.

11)If the user runs out of attempts (i.e., the loop finishes without finding the correct number), a failure message is displayed along with the correct answer. The displayFarewellMessage() method is called.

12)The celebrateVictory() and displayFarewellMessage() methods are private helper methods that display celebratory or farewell messages respectively.
