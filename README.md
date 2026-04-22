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

### CPU Difficulty (vs CPU mode only)

| Level | Behaviour |
|---|---|
| **Easy** | CPU picks a random empty cell |
| **Hard** | CPU plays a perfect strategy using minimax — cannot be beaten, only drawn |

### Rules

- The board is a 3×3 grid.
- **X always goes first.**
- Players take turns clicking an empty cell to place their mark.
- The first player to get **3 marks in a row** (horizontally, vertically, or diagonally) wins.
- If all 9 cells are filled with no winner, the game is a **draw**.

### Player Names

Click either player name in the scoreboard to rename them. The name updates in all status messages immediately. In vs CPU mode the O label is locked to "CPU".

### Controls

| Button | Action |
|---|---|
| **New Game** | Clear the board and start a fresh round (scores are kept) |
| **Undo** | Revert the last move — available in 2-player mode only |
| **Reset Score** | Clear the board and reset all scores to zero |
| **♪ Sound** | Toggle sound effects on/off |

### Scoring

The scoreboard tracks **X Wins**, **O Wins**, and **Draws** across rounds. Scores carry over until you click **Reset Score**. The result of the last completed round is shown below the controls.

### Tips

- Aim for the **centre or corners** first to maximise your winning options against a human opponent.
- On **Easy** CPU you can win — on **Hard** the best you can achieve is a draw.
- Winning cells **pulse** to highlight the result at the end of each round.

## Requirements

- Any modern web browser (no internet connection required after download).
