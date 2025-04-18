# 🏁 Checkers Game in C (with AI using Minimax Algorithm)

This is a terminal-based **Checkers (Draughts)** game written in **C language**, featuring:
- A **two-player** mode for local play.
- A smart **AI opponent** using the **Minimax algorithm** with evaluation logic.

---

## 🎮 Features

- 8x8 classic Checkers board.
- Turn-based movement for white and black pieces.
- Basic king promotion logic.
- AI opponent makes optimal moves using recursive **Minimax algorithm**.
- Evaluation function for deciding the best possible move.
- Clear console-based interface with board visualization.

---

## 🤖 AI: Minimax Algorithm

The AI in this game uses the **Minimax algorithm** to:
- Simulate possible moves up to a certain depth.
- Evaluate the position based on material advantage.
- Maximize its advantage while minimizing the opponent’s.

---

## 🧠 Core Functions

| Function | Description |
|---------|-------------|
| `minimax()` | Recursive implementation of minimax logic for AI. |
| `evaluate()` | Returns a score based on the number of pieces and positions. |
| `bestmoves()` | Calculates the best move AI can make. |
| `swappositions()` | Moves pieces and updates the board. |
| `printboard()` | Prints the board in a visual format to the terminal. |

---

## 🎯 How to Play

1. Compile the code using any C compiler (e.g., GCC).
   ```bash
   gcc -o checkers checkers.c
   ```
2. Run the game:
   ```bash
   ./checkers
   ```
3. Follow the instructions to move pieces.
4. The board will update each turn.

---

## 🧱 Piece Representation

| Symbol | Meaning |
|--------|---------|
| `w`    | White piece (human) |
| `W`    | White king (human) |
| `b`    | Black piece (AI) |
| `B`    | Black king (AI) |
| `.` or ` ` | Empty |

---

## 🛠️ Requirements

- C Compiler (e.g., `gcc`, `clang`)
- Compatible with Linux, Windows, or macOS terminal

