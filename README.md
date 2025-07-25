# Mini-Chess-Engine
# Beginner Chess Engine using DSA (No AI)

This is a beginner-friendly command-line chess engine built using Python and the `python-chess` library. It allows a user to play as White against an AI that uses classical Data Structures and Algorithms (DSA) — specifically, the **Minimax algorithm** — to make decisions. This engine does not rely on machine learning or databases; it's entirely based on logic and computation.

## Features

- Full game: You (White) vs AI (Black)
- AI uses Minimax algorithm to calculate best moves
- Evaluation based on material count (simplified scoring)
- Top 3 suggested moves after every AI turn
- Fully command-line based; no GUI or external dependencies

## How DSA is Used

This project demonstrates how traditional DSA concepts power a simplified chess engine:

### 1. Tree Traversal (Minimax Algorithm)
- Explores a game tree of moves using **recursive depth-limited search**.
- Alternates between maximizing and minimizing player's score.

### 2. Board Evaluation
- Uses a scoring function based on material values (e.g., Queen = 9, Pawn = 1).
- Uses dictionary lookups and board state traversal.

### 3. Move Sorting and Suggestion
- Evaluates all legal user moves and ranks them.
- Suggests the top 3 moves using sorting techniques.

## Requirements

This project uses only one external dependency:

```bash
python-chess

