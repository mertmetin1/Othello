
# 📌 **Othello AI Game**

This project is a **Java-based Othello (Reversi) game** where players can compete in **Human vs Human**, **Human vs AI**, or **AI vs AI** modes. The AI player utilizes **Minimax Algorithm with Alpha-Beta Pruning** to determine the best move.

![generative-ai vs-traditional-ai](https://github.com/user-attachments/assets/d8a3a248-5e01-43ab-946a-9025e44e86cd)

---

## 🚀 **Features**
- **Multiple Game Modes:**  
  - Human vs Human  
  - Human vs AI  
  - AI vs AI  
- **Advanced AI Mechanics:**  
  - Minimax Algorithm  
  - Alpha-Beta Pruning  
  - Customizable Depth (Ply) and Heuristic Strategies  
- **Dynamic Board Representation:** The game board is automatically initialized with the standard Othello setup.  
- **Move Validation & Execution:** Ensures all moves are valid before execution.  
- **Score Tracking:** Displays the final score and determines the winner.  

---

## 📂 **Project Structure**
```
📦 Othello_AI_Game
 ┣ 📜 AIPlayer.java  # AI player logic and best move calculation
 ┣ 📜 Board.java     # Game board representation, validation, and score calculations
 ┣ 📜 Game.java      # Main game flow (mode selection, gameplay logic)
 ┣ 📜 AITest.java    # AI performance evaluation with different settings
 ┣ 📜 README.md      # Project documentation
```

---

## 🛠 **Installation & Execution**

### 1️⃣ **Prerequisites**
This project requires **Java (JDK 8+)**. If you haven't installed Java, you can download it here:
- [Download Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)

### 2️⃣ **Running the Project**
Once Java is installed, follow these steps to run the game:

```sh
# Navigate to the project directory
cd Othello_AI_Game

# Compile the Java files
javac *.java

# Run the game
java Game
```

---

## 🎮 **How to Play**
![HD-wallpaper-othello-board-game-reversi](https://github.com/user-attachments/assets/60bd9726-2ea9-4aee-b4a5-73d0422cb7f3)
When you start the program, the following menu appears:

```
Choose mode:
1. human vs human
2. human vs AI
3. AI vs AI
```

| Game Mode          | Description |
|--------------------|------------|
| **1 - Human vs Human** | Two players take turns making moves. |
| **2 - Human vs AI** | The player plays as **X**, while the AI plays as **O**. |
| **3 - AI vs AI** | Two AI players compete against each other. |

---

## 🔍 **Technical Details**
### 🎯 **AI Algorithm**
The AI player utilizes the **Minimax algorithm with Alpha-Beta pruning** to determine the best move.

- **Minimax Algorithm:** Evaluates all possible moves and selects the optimal one.
- **Alpha-Beta Pruning:** Reduces the number of evaluations to improve performance.

### 🧠 **Heuristic Functions**
The AI evaluates the board state using different **heuristic functions**:

1. **H1 - Stone Count Heuristic:** Evaluates the score difference between players.
2. **H2 - Positional Weights:** Considers board positions with strategic importance.
3. **H3 - Corner & Edge Risks:** Evaluates the advantage of corner and edge placements.


## 📊 **Example Game Output**
```
Choose mode:
1. human vs human
2. human vs AI
3. AI vs AI

Enter your move (e.g., d3):
> d3

AI O plays: f5
...

Game Over
Score - X: 24, O: 40
```

---

## 🏆 **Future Improvements**
📌 If you'd like to enhance this project, consider adding:
- **Graphical User Interface (GUI)** for a better visual experience.
- **Deeper AI analysis** by tracking move statistics.
- **More advanced heuristic strategies** for improved AI decision-making.

