# JS-TIC-TAC-TOE-GAME


### OBJECTIVE:
This project for aims to develop a Tic Tac Toe game using javascrypt. It mainly consists of developing and implementing a computer program that plays Tic Tac Toe against another player.<br/>
In order to understand what Tic Tac Toe game is and how to play the game, below is the description.

### GAME DESCRIPTION:
Tic Tac Toe is a two-player game (one of them being played by computer or human). In this game, there is a board with 3 x 3 squares.<br/>

The two players take turns putting marks on a 3x3 board. The goal of Tic Tac Toe game is to be one of the players to get three same symbols in a row - horizontally, vertically or diagonally on a 3 x 3 grid.  The player who first gets 3 of his/her symbols (marks) in a row - vertically, horizontally, or diagonally wins the game, and the other loses the game. 
The game can be played by two players.

### GAME RULES:
A player can choose between two symbols with his opponent, usual game uses “X” and “O”. 
1.	The player that gets to play first will get the "X" mark (we call him/her player 1) and the player that gets to play second will get the "O" mark (we call him/her player 2).

2.	Player 1 and 2 take turns making moves with Player 1 playing mark “X” and Player 2 playing mark “O”.

3.	A player marks any of the 3x3 squares with his mark (“X” or “O”) and their aim is to create a straight line horizontally, vertically or diagonally with two intensions:<br/>
a.	One of the players gets three of his/her marks in a row (vertically, horizontally, or diagonally) i.e. that player wins the game.<br/>
b.	If no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a  draw/tie.

### IMPLEMENTATION PLAN:
The implementation workflow for this project is as follows:

<p align="center"><img src="/img/JavaScript-logo.png" width="430" height="400" /></p>

In order to visualize the defined game rules and description, the game is shown in Figures below.

First the game will start with empty board.<br/>

<p align="center"><img src="/img/theBoard.png" width="280" height="280" /></p>

Then Player 1 will make his/her move by playing mark “X” on this board. Then Player 2 will make his/her move by playing mark “O” on this board. This will keep on continuing until the board is full of marks.

Then the program will check if Player 1 with “X” wins or Player 2 with “O” wins and that scenario will be follows: (could be vertically, horizontally or diagonally).  

<p align="center"><img src="/img/xWins.png" width="280" height="280" /></p>

If none of the players win, the program will check for draw.

<p align="center"><img src="/img/itsDraw.png" width="280" height="280" /></p>

### TECHNOLOGIES USED

* HTML5

* CSS3

* Javascript (simple)

<p align="center"><img src="Images/EmptyBoard_highlightedButtons.png" width="280" height="280" /></p>

* The game contains one button showned at the end of the game, either it is draw or win for some of the players, so that we can do restart the game and start it again. Once we click button, "restart" start playing game by clicking on the game board. Since we play first, we will be defined as Player X. 

* Once the game is finished, the message will be displayed on the game screen with either the winner name (X or O) or Draw game.