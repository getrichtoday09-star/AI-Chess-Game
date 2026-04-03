♟️ AI Chess Game Master
Welcome to the AI Chess Game Master! This project is a complete, interactive, Python-based chess application where users can test their strategic skills against a custom-built Artificial Intelligence.

Featuring full move validation, custom piece logic, game state tracking, and an intelligent AI opponent, this project goes beyond a simple chessboard by acting as a true "Game Master." It tracks your progress, enforces the rules of the game, and dynamically calculates the best mathematical moves to challenge players of all levels.

🚀 Key Features
🧠 Custom AI Opponent (chessai.py): Play against a computerized Game Master. The AI evaluates board states, calculates material advantages, and predicts future moves to provide a challenging match.

⚖️ Strict Rule Enforcement (rules.py & pieces.py): Complete implementation of chess logic. Handles everything from basic piece movement to complex mechanics like castling, en passant, and pawn promotion.

💾 Match Tracking & Database (db.py & track.py): The Game Master remembers! The built-in database tracks game histories, player statistics, and match outcomes.

🎮 Interactive Gameplay (play.py & chessgame.py): A smooth, interactive user experience to make your moves, view the board, and interact with the Game Master.

📂 Project Structure
Here is an overview of the core architecture based on the repository files:

play.py - The main entry point to launch the game interface.

chessgame.py - Manages the core game loop, turn switching, and rendering the board state.

chessai.py - The brain of the operation. Contains the search algorithms (e.g., Minimax, Alpha-Beta pruning) and board evaluation logic for the AI.

rules.py - The rulebook. Validates legal moves, checks for checks/checkmates, and handles edge cases.

pieces.py - Object-oriented definitions for all chess pieces (Pawns, Knights, Bishops, Rooks, Queens, Kings) and their specific movement patterns.

db.py & track.py - Handles database connections, saving match data, and loading player statistics.

test.py - Unit tests to ensure the rules, AI, and game states function perfectly.

requirements.txt - The list of Python dependencies needed to run the project.

🛠️ Tech Stack
Language: Python

AI Logic: Custom-built position evaluation and decision tree search.

Data Persistence: SQLite / Python native database handling (via db.py).

UI/Rendering: (Assuming Pygame or Terminal-based, determined by chessgame.py).

📦 Installation & Setup
Follow these steps to challenge the Game Master locally:

How to Play:

Once the game launches, you will be prompted to start a new match.

Make your moves (via click or algebraic notation depending on your UI).

The AI Game Master will evaluate the board and respond instantly.

Check your stats anytime to see how you measure up against the machine!

📝 Upcoming Features

Implement deeper AI search depth (adjustable difficulty).

Opening book integration for the AI.

Graphical user interface (GUI) enhancements.

Multiplayer local mode.
