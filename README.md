Overview 

Chess Engines are computer programs that provides a structural design to play chess. Technologies like artificial intelligence and different algorithms are used to analyze positions, calculate positions, calculate possible moves, and determine the best move based on the approach of algorithms. Evaluation function has to be used to access the strength of a given chess position. 

Chess engines use data structures to represent the current state of the game board, including the positions of pieces and their legal moves.

To decide the best move, the engine explores possible future moves and their outcomes. This is often done using algorithms like minimax with alpha-beta pruning, which efficiently searches through the game tree to find the optimal move.

Chess engines assign numerical values to positions on the board to assess the desirability of different moves. These evaluations consider factors such as piece mobility, material advantage, king safety, pawn structure, and positional control.

Examine whether certain styles of play or openings are favored, and develop methods to ensure fairness and diversity in the engine’s recommendation.


![image](https://github.com/whitehatmaou/Chess-Engine/assets/126908141/748b6b30-eb2f-4a25-b420-e73e5c6fd333)


Methods OR Tools OR Algorithms used


MiniMax Algorithm

  Minimax is a kind of backtracking algorithm that is used in decision making and game theory to find the optimal move for a player, assuming that your opponent also plays optimally. It is widely used in two player turn-based games such as Tic-Tac-Toe, Backgammon, Mancala, Chess, etc.
In Minimax the two players are called maximizer and minimizer. The maximizer tries to get the highest score possible while the minimizer tries to do the opposite and get the lowest score possible.


Alpha-Beta Pruning

  Alpha Beta Pruning is an optimization technique of the Minimax algorithm. This algorithm solves the limitation of exponential time and space complexity in the case of the Minimax algorithm by pruning redundant branches of a game tree using its parameters Alpha(α) and Beta(β).
)

Experimentation and Results

System Specifications
 	Execution Time – The execution time of the program is 200 				  nanoseconds.
	Technology used – Programming Language 'Java' is extensively 			        used in the Chess Engine. To run this program, 			        it is required to use Java SDK 1.8.0.


![image](https://github.com/whitehatmaou/Chess-Engine/assets/126908141/6c612312-10c6-44dc-972f-5081b2b4a637)

Key Findings

Chess Engine has been manually being played with the current strongest chess engine stockfish 16 level 5 resulting in an accuracy of 88%.

All the legal moves has been played using this chess engine.

Special moves like en passant and castling of king has been left out which will be used in further production.

Bitboards and other advance algorithms will be used in the further production of the chess engine to provide faster analysis of the moves in the chess board.


