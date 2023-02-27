Questions
How do we only allow one button click per tile? 
How do we get state again?
Visit past projects for examples
How does a INT work again?
How to make a board?
How do i get bootstrap to work again?
How do i create elements using javascript?
How do i change turns on ‘click’ Event?





WHAT SHOULD I DO

Set bootstrap to make a board on INT.
Load all ‘click’ EventListeners on each number in the array on INT.
Restart ‘btn’ at bottom of the page on INT.
Pick your own X/O style EX. img or even a broader version of X/O
Using bootstrap on a div to make it .col-4








HTML/CSS
Conditional rendering
Is it an X in the square or a O
Who wins? X or O or also if the Cat

Atoms
Tiles
Using bootstrap on a div to make it .col-4

Div.container
	Div.row
		div.col-4

Organism
Tiles - click events
Board as whole
Buttons (restart)


Objectives
The game should let the players know who's turn it is.
Player x or player O
Remove EventListeners
Game tiles should only be clickable once
if the game is over they should not be clickable at all.
The game should display who wins the game if someone wins, otherwise, say that the game resulted in a tie.
There should be a Restart Game button that does not refresh the page (set state).
On each player’s turn, that player places one of their symbols on an unoccupied space by clicking.
The game continues until one player places three symbols in a straight line (horizontal, vertical, or diagonal) and wins or there are no remaining available spaces and it is a draw.
Only have a single <div id="app"></div> in your index.HTML (try to code golf the HTML file)


Variables
STATE 
	currentPlayer
	boardState = [] (NINE SPOTS)
	winConditions
		[0,1,2]
		[3,4,5]
		[6,7,8]
	[0,3,6]
		1,4,7
		2,5,8
		0,4,8
		2,4,6

Functions
init()
checkWin()
switchPlayer()
If currentPlayer == ‘X’
currentPlayer = ‘O’
Else
currentPlayer = ‘X’
makeMove()
Adds the current player to the tile clicked
checkWin()
If win do endGame()
else
Switches the currentPlayer in state
Removes the eventListener
endGame()
Display the winner of the game
Remove all event listeners
Show reset game button

resetGame()
Drawboard
Resets state to initial values
Procedures

INIT
	Draw the board
	For each tile drawn, add a click listener to it


START



