# SUDOKU SOLVER
This repository contains a simple implementation of the classic Sudoku Solver using 
  * Apache NetBeans IDE
  * Java Swing Library
  * AWT Library
  * Maven Dependency

# Summary
* The project is a game that allows the user to solve Sudoku puzzles.
* The aim of the project is to recreate the experience of solving Sudoku puzzles that people used to do in newspapers.
* The game consists of a 9x9 grid of boxes which are 9 rows and 9 columns, which are buttons that can be clicked to fill by selecting the digits from 1 to 9 in the box.
* The game has a reset button, an exit button, a solution button, and a check moves button.
* The reset button empties the whole grid, the exit button closes the execution, the solution button fills the grid with expected solutions, and the check moves button checks whether the previous moves are correct or not.

# How It Looks

## Home Page
![home](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/5f52abbd-6000-4f13-8c9e-c475735a73b3)
Click the Get Started Button on the Home page screen to load the Sudoku Solver Game.

## Sudoku Solver
![gameplay](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/d725b398-fe3d-4056-9792-d52e0b91bf42)
As the name indicates, the project is to solve a Sudoku puzzle, the ultimate game of patience and perseverance.
Sudoku is a combinatorial number-placement puzzle with a 9 x 9 cell grid partially filled in with numbers from 1 to 9. The goal is to fill the remaining, blank fields with the rest of the numbers so that each row and column will have only one number of each kind.

# How to Setup the Game
* Just download the SUDOKU_Solving file from Sudoku Solver or from this link.
* Run the jar file. You will be directed to the homepage.
* Click on the "Get Started" button to start the game.
* Now put your brain into solving the puzzle and enjoy the gameplay according to the "Gameplay" and "Game Functionalities" descriptions given below.
* If the game is over, press the Reset button to start playing again. You can also press the X (close) button or Exit button and confirm by clicking "Yes" to exit, or "No" to replay.

# Gameplay Overview With Snaps
Let you know about the friendly interface of the game panel, and how it looks from the top to bottom of the page and shows the numbers that are previously fed in the panels in different grid backgrounds. This also lets us know that the grids are already solved and non-editable. And it shows empty spaces where the numbers are to be fed.

## No Number Selected Alert 
This is the main image and this window or this point in time is letting us know that here you have selected no number with the popup and also mentions the feature added by me to the message which lets the player know that you need to select any number in between feeding the numbers. 

![numberseletion](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/4517ce84-d939-474c-be29-9e1d43224f59)


## Already Allocated Fields:
We can not enter any number into those fields which are already allocated.

![selected](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/e19d5291-4d78-418a-ac3a-404c7db9f355)


## Start solving the puzzle
This stage is stage lets you enter the desired number in the blank spaces which you make ahead step to solve the sudoku, For the number 5 you select multiple numbers the more you move ahead in the game.

![solving](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/5cfb5ae3-430f-4674-9c24-4efc4a0b1d12)


# Game Functionalities
There are four buttons with four main functionalities, 

## Check Moves: 
This is the stage of the game that lets you know about the working or the quality checking of the. It will be transferred as the button named "Remove Wrong"
  
  ![wrongmoves](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/d845d052-41b4-494a-b5bc-581e234bdbbb)

## Remove Wrong: 
By clicking this button we can remove the wrong entry done by us, and then it will be transferred to "Check Moves" again.
  
  ![solving](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/54c2a440-e10d-4dff-964a-f6209dc01456)

## Solution: 
This is the screen of the solution button which lets us be aware of the proper answer or the proper number entered at its proper place. After that, we can revome the solution by the same button but it is named "Hide Solution", After removing the solution it will transfer to "Solution" again.
  
  ![solved](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/61f171d2-b28e-4912-a79f-7a89fa6e6f76)
  ![checksolution](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/3a4aebb2-fec1-4f7c-8279-aebec1249928)


## Reset: 
This is also a good feature of our project which lets you know about the reset button or reset facility It clears numbers whether you have solved it or not.

  ![reset](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/c017c4a9-b341-42a6-ba2b-eae3b7db60b6)


## Exit: 
This is a button where we get the feature of checking the capability of the exit button which first asks you to exit (y/n) yes or no. Then you select the proper term and move ahead.
  
  ![exit](https://github.com/Garaisourav12/SUDOKU_Solving/assets/101336956/52445d95-3f73-4aaf-a2b4-1b2696b75b2c)

# Upcoming Updates
 * A random puzzle will be generated after every time reset.
 * Every puzzle will be solved by the sudoku-solving algorithm using backtracking and recursion.
 * After solving the puzzle correctly if you press on the "Check Moves" button it will show a pop-up with a "Congratulations" message and give options of Restarting with a new puzzle or to Exit.
 
# References
 * IDE or text editor: Like Apache NetBeans IDE 18 etc.
 * Java runtime environments installed. Refer to Oracle's official documentation.
 * Get support and information about the Java language from Oracle.
 * Stay updated with the latest version releases at the official build.
