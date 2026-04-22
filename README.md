# Tic Tac Toe

A browser-based Tic Tac Toe game. No installation required — just open one file and play.

## How to Run

1. Download or clone this repository.
2. Open `tictactoe.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. The game starts immediately — no server or build step needed.

## How to Play

### Game Modes

| Mode | Description |
|---|---|
| **2 Players** | Two people take turns on the same screen |
| **vs CPU** | Play against an AI opponent |

### Rules

- The board is a 3×3 grid.
- **X always goes first.**
- Players take turns clicking an empty cell to place their mark.
- The first player to get **3 marks in a row** (horizontally, vertically, or diagonally) wins.
- If all 9 cells are filled with no winner, the game is a **draw**.

### Controls

| Button | Action |
|---|---|
| **New Game** | Clear the board and start a fresh round (scores are kept) |
| **Reset Score** | Clear the board and reset all scores to zero |
| **2 Players / vs CPU** | Switch game mode (resets the current game) |

### Scoring

The scoreboard at the bottom tracks **X Wins**, **O Wins**, and **Draws** across multiple rounds. Scores carry over until you click **Reset Score**.

### Tips

- In **vs CPU** mode the AI plays a perfect strategy using the minimax algorithm — it cannot be beaten, only drawn.
- Aim for the **centre or corners** first to maximize your winning options.
- Winning cells will **pulse** to highlight the result at the end of each round.

## Requirements

- Any modern web browser (no internet connection required after download).
