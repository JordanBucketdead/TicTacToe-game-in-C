# TicTacToe-game-in-C
Basic Tic Tac Toe game
The integers userTurn and computerTurn, are initialized to -1. These variables will be used to store the user's and the computer's moves during the game.
The random number generator is used by the program with a seed value that is based on the current time. 
This helps to ensure that the random numbers generated during the game are not predictable.
A while loop will continue as long as the checkWinner() function returns 0. 
The checkWinner() function likely checks the current state of the game to see if either the user or the computer has won or if the game has ended in a tie.
Another while loop will continue as long as userTurn is equal to -1 or the position on the game board corresponding to userTurn is not equal to 0.
The purpose of this loop is to ensure that the user chooses a valid move by typing a number between 0 and 8 that corresponds to an unoccupied position on the game board.
The user has to enter a number between 0 and 8 and then read in the user's input using scanf(). The value entered by the user is stored in the userTurn variable.
I used if statements to print the board where "." is the unoccupied position, x is player 1 and 0 is player 2 then I used if tsatements to check the winner according to columns, rows and diagonals
