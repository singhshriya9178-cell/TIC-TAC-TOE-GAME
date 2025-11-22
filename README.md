Tic-Tac-Toe in C

A simple terminal-based Tic-Tac-Toe game written in C.
Two players (X and O) take turns entering their moves on a 3×3 grid.
The game checks for wins, draws, and handles invalid moves.

🎮 Features

3×3 Tic-Tac-Toe board

Player vs. Player mode

Input validation (prevents overwriting moves or invalid positions)

Win detection (rows, columns, diagonals)

Draw detection

Simple and clean code structure

📂 Project Structure
/tic-tac-toe
│
├── main.c          # Source code of the game
└── README.md       # Project documentation

🚀 How to Compile

Use any C compiler. For GCC:

gcc main.c -o tictactoe

▶️ How to Run
./tictactoe

🕹️ How to Play

The board positions are indexed by rows and columns (1–3)

On each turn, the game asks for:

Player X, enter row (1-3) and column (1-3):


Enter numbers like:

1 3   → Top-right
2 2   → Center
3 1   → Bottom-left


Player X goes first, then O.

A player wins when they align three marks horizontally, vertically, or diagonally.

If all 9 cells fill up with no winner → Draw.

📸 Example Game
 X | O | X
---+---+---
 O | X |  
---+---+---
   |   | O

Player X wins!

🛠️ Requirements

C Compiler (GCC, Clang, or MSVC)

Works on Linux, Windows, macOS

👨‍💻 Author
SHRIYA SINGH
📧 Developed as a mini project using pure C language.

📧 Contact
Personal Mail: -singhshriya9178@gmail.com
Business Mail - singhshriya9178@gmail.com
College Mail - 250301120309@centurionuniv.edu.in
🧾 License
This project is comppletely open-source .

![image alt](
