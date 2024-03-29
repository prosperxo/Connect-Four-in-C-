
This is a simple text-based implementation of the classic Connect 4 game written in C++. Players take turns dropping colored discs into a grid, aiming to connect four of their discs vertically, horizontally, or diagonally before their opponent does.

Features
Text-based interface for easy gameplay.
Supports two players taking turns.
Checks for win conditions after each move.
Handles invalid moves and draws.
How to Play
Compile the Code: Compile the provided C++ code using a C++ compiler. If you have g++ installed, you can compile the code by running g++ connect4.cpp -o connect4.

Run the Executable: Execute the compiled program by running ./connect4 in your terminal or command prompt.

Gameplay: Follow the prompts to enter column numbers for your moves. The game will display the current state of the board after each move.

Winning: The game ends when one player successfully connects four of their pieces vertically, horizontally, or diagonally. The program will declare the winning player and end the game.

Draw: If no player achieves a winning condition after 21 moves, the game ends in a draw.

Example Gameplay
mathematica
Copy code
Welcome To Connect4 !!
1|2|3|4|5|6|7|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,,|,|,|,|
,|,|,|,|,|,,|
,|,|,|,|,|,|,|
Player1
Enter column: 4
1|2|3|4|5|6|7|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|X|,|,|,|
Player2
Enter column: 3
1|2|3|4|5|6|7|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|,|,|,|,|
,|,|,|O|,|,|,|
,|,|,|X|,|,|,|
...
License
This project is licensed under the MIT License.

