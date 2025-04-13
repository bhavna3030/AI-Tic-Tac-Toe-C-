 AI Tic Tac Toe (Minimax Algorithm) – C++ Project

 Overview
This is a console-based **Tic Tac Toe game** built in C++ where a player competes against an unbeatable **AI opponent**. The AI uses the **Minimax algorithm**, ensuring it always plays optimally.

 Features
-  Player vs AI mode  
-  Intelligent move selection using **Minimax**  
-  Win/draw detection logic  
-  Interactive CLI with board visualization  
-  No external libraries required

 Minimax Algorithm
The AI simulates all possible outcomes of the game and picks the move that **maximizes its chance of winning** (and minimizes the chance of the opponent winning).

**Evaluation:**
- Win → +10  
- Lose → -10  
- Draw → 0  

**Decision Tree:**  
Recursively explores each possible move, simulates the opponent's response, and selects the best path.

 Preview
```
 X | O | 3
-----------
 4 | O | X
-----------
 X | 8 | 9

Computer wins!


 How to Run

 Requirements:
- Any C++ compiler (g++, clang++, or an IDE like Code::Blocks or Visual Studio)

 Compile:
bash
g++ tictactoe.cpp -o tictactoe./tictactoe


 Project Structure
```
tictactoe.cpp    // Contains all source code and logic
README.md        // Project documentation
```

 Concepts Used
-  2D Arrays  
-  Recursion and Backtracking  
-  Minimax Decision Making  
-  Input Validation  
-  Game Loops

 License
This project is open-source and free to use under the MIT License.
