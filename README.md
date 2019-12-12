# AI_Chess
This is a javascript based AI incorporated chess game.

The game is implemented using a GUI which was built using chess.js and chessboard.js libraries. For implementing the algorithm
for chess moves, I have used minimax algorithm which helps AI in deciding the best possible moves based on the score given to 
each piece of the chess board.

Furthermore, the minimax algorithm was improved by using alpha-beta pruning algorithm. The chessboard styling and piece placement 
was built using chess.js and chessboard.js which is then combined with the javascript algorithm built for piece move making,
and other relevant decisions.

At the start of the game chessboard looks as shown below.

![Chess_Game](https://github.com/Palash09/AI_Chess/blob/master/Initial_ChessBoard.png)

Below the chessboard, we can select the maximum depth to which the AI will search for the best possible move. 
Here, as the search depth increases the toughness level of the game will increase and our AI will perform better.

The time is also displayed which is taken to complete the move by the players.

Along with this various chess locations are printed where the pieces are moved by the AI and the player.

![Chess_Game](https://github.com/Palash09/AI_Chess/blob/master/ChessBoard.png)

