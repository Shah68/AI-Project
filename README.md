# AI-Project
A project using AI to build Tic Tac Toe game.

The project is to build a Tic Tac Toe game with Minimax Algorithm. Tic Tac Toe is basically a 3x3 grid game where two symbols are used which are X and O. As the game begins it will randomly assigns the player and the computer (AI agent) which sysmbols they will use to play the game.

# Conditions
1. Winning:- To win the game player has to make three same combinations of their given sysmbols either horizontally, vertically, or diagonally, any player that makes the combination first will win the game.
2. Losing:- If the competitor made the combination of symbols first then the player will lose the game.
3. Drawing:- If any player cannot make the combination and all the cells in the grid then the game will result in a draw.

# Features
1. Random Symbol Assignment:- This feature will be used to assign the symbols to the player randomly when they start the game.
2. User Friendly Input:- In the 3x3 grid of the game, player can put their assigned symbol in any cell of the grid.
3. Scores Calculation and Display:- Scores of the player and AI agent (computer player) will be shown on the side display in the game.
4. Animated Match Display:- This feature works when anyone of the player wins the game, when the player wins the game an imaginary line will connect the combination of sysmbols highlightning the pair of winning symbols.
5. Turn Indication:- In the side panel of the game below the scores, a brown box will hover on the symbol indicating whose turn is there either the player or the AI agent.
6. Draw Handling:- If the game is over and player want to start a new game then this feature will clean the board.
7. Persistent Score Storage:- If the player/user wants to close the program after playing some games, then this feature will be used to save the scores of the previous game.
8. Reset:- If the player want to reset the scores of the game, then they can reset it by hitting the "reset" button on the side panel.
9. Quit:- To quit the game player can press "Q".

# Tools and Libraries used
- Python.
- Visual Studio.
- OpenCV.
- numpy.
- Random.
- Pickle.
