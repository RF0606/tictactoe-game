# Changelog

## [v1.1] - 2026-04-22

### Added
- **CPU difficulty selector** — Easy (random moves) or Hard (unbeatable minimax); shown only in vs CPU mode
- **Player name customisation** — click either name in the scoreboard to rename; CPU label is locked in vs CPU mode
- **Sound effects** — Web Audio API tones for placing a piece, winning, and drawing; toggled with the Sound button (no external files required)
- **Undo** — reverts the last move in 2-player mode; disabled during CPU turns and after the game ends
- **Last round result** shown below the controls after each game ends

## [v1] - 2026-04-22

### Added
- Tic Tac Toe game playable in the browser (single HTML file)
- 2-player mode (shared screen, alternating turns)
- vs CPU mode using minimax algorithm (unbeatable AI)
- Score tracking: X wins, O wins, draws — persists across games
- Animated pulse highlight on winning cells
- New Game and Reset Score controls
