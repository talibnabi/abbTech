# abbTech
homeworks 

**HOMEWORK 1**
Arrays

The task is
Write a program called "numbers", which makes a random number and offers the player to guess it.

Technical requirements:

With the help of java.util.Random the program makes a random number in a range [0-100] and invites the player through a console to enter the name which is saved in the variable name.
Before the beginning, show up given text on screen: Let the game begin!.
The whole process of the game is processed in an infinite cycle.
The player is invited to enter the number in the console, after which the program compares the hidden number with the fact that the user has entered.
If the entered number is less than a random number which the program has generated, you should to display the text: Your number is too small. Please, try again.. If the entered number is more than the number which the program has generated, you should display the text: Your number is too big. Please, try again..
If the entered number is equal to the number which the program has generated, it is necessary to display the text on the screen: Congratulations, {name}!.
The task must be performed using arrays (DO NOT USE THE INTERFACES List, Set, Map).


Advanced complexity. Not necessary to implement:

Before the every next iteration, the program saves the number entered by the user into the array. After the player has guessed the number, before an exit, the program displays the text on the screen: Your numbers:  and shows all the numbers entered by the player, sorted from larger to smaller.
Add a check for correctness of the data. While the user enter is not a number - ask him to enter the number again.
Add a little more sense into the game: let the predicted number be the year of the well-known event. Information about years is stored in a two-dimensional array [year X event]. The program starts and choose a cell in a matrix by the random way and displays, for example: When did the World War II begin?.


**HOMEWORK 2**
Arrays

The task is
Write a program called "shooting at the square."

Technical requirements:

Given a 5x5 square, where the program randomly sets a target.
Before the game starts, the text is displayed on the screen: All set. Get ready to rumble!

The whole process of the game is processed in an infinite loop.
The player is asked to enter a line for fire; the program checks that the  user enter is a number, and this entered number is in the range of playing field lines (1-5). As long as the player makes mistakes, he will be asked to enter the number again.
The player is asked to enter a shooting bar (must pass the same check).
After each shot, the updated game field should be displayed in the console. Cells, where the player has already shot is necessary to note as * .
The game ends when the target is defeated. At the end of the game, display the phrase in console: You have won!. The target should be marked as x .
The task must be done using arrays (DO NOT USE THE INTERFACES List, Set, Map).

An example of console output:
 0 | 1 | 2 | 3 | 4 | 5 |
 1 | - | - | - | - | - |
 2 | - | * | * | - | - |
 3 | * | - | - | * | - |
 4 | - | - | - | - | * |
 5 | * | - | * | - | - |

Advanced complexity. Not necessary for the realization:

Add an "area shooting" feature, so that the target occupies 3 cells (horizontally or vertically) and the affected compartments are marked with x.
