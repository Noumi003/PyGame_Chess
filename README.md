# ♟️ Two Player Chess (Pygame)

A local two-player chess game built using Python and Pygame.
This project focuses on implementing core chess mechanics from scratch, including piece movement, turn handling, and basic game state management.

# 📌 Overview

This is a fully interactive chess game where two players can play against each other on the same computer. The game renders a graphical chessboard, handles piece selection, validates moves, and tracks captured pieces.

The main goal of this project was to better understand:

- Game loops in Pygame
- Grid-based movement systems
- Handling complex rule-based logic (like chess)

# 🎮 Features

- Two-player local gameplay
- Fully rendered 8×8 chessboard

Individual movement logic for all pieces:
- Pawn
- Rook
- Knight
- Bishop
- Queen
- King
- Turn-based system (White → Black)
- Valid move highlighting
- Piece selection highlighting
- Capture system with side display
- King-in-check visual indicator
- Game over detection (king captured)
- Restart functionality
- Forfeit option

# 🧠 How It Works

- Game State

The game tracks:

- Piece types (white_pieces, black_pieces)
- Piece positions (white_locations, black_locations)
- Captured pieces
- Current turn (turn_step)
- Selected piece and valid moves
- Move Validation
Allow capturing enemy pieces
