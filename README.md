# Chess Game ♟️

A two-player chess game built with Python and Pygame. The game provides a graphical chessboard, piece movement, move highlighting, captured-piece tracking, and basic check detection.

## Features

- **Two-player gameplay:** Play locally with White and Black taking turns.
- **Graphical chessboard:** An 8×8 board with selectable chess pieces.
- **Move highlighting:** Displays available moves for the selected piece.
- **Piece capturing:** Captured pieces are removed from the board and displayed on the side.
- **Check detection:** Highlights the king when it is under attack.
- **Win detection:** Declares a winner when the opponent's king is captured.
- **Forfeit option:** Allows a player to concede the game.
- **Restart:** Press `ENTER` to start a new game after the game ends.
- **Online piece images:** Downloads chess-piece images and removes their backgrounds using `rembg`.

## Technologies Used

- Python
- Pygame
- Requests
- rembg
- BytesIO

## Requirements

- Python 3.10 or later recommended
- An internet connection to download the chess-piece images on startup

## Installation

1. Clone the repository:

   ```bash
   git clone 'https://github.com/mahmoudfawzy22/chess_game'
   ```

2. Navigate to the project directory:

   ```bash
   cd 'chess_game'
   ```

3. Install the required libraries:

   ```bash
   pip install pygame requests rembg
   ```

4. Run the game:

   ```bash
   python main.py
   ```

   Replace `main.py` with the name of your Python file if it is different.

## How to Play

1. Launch the game.
2. White starts first.
3. Click one of your pieces to select it.
4. Click a highlighted square to move the selected piece.
5. Players alternate turns after each move.
6. Capture the opponent's king to win, or click **FORFEIT** to concede.

## Controls

| Action                  | Control                           |
| ----------------------- | --------------------------------- |
| Select a piece          | Left mouse click                  |
| Move a piece            | Left mouse click on a destination |
| Forfeit the game        | Click **FORFEIT**                 |
| Restart after game over | Press `ENTER`                     |
| Quit the game           | Close the window                  |

## Project Structure

```text
chess-game/
├── main.py
└── README.md
```

The structure above is an example. Your project may contain additional files.

## Notes

- The game implements basic piece movement and capture rules.
- Full official chess rules, including castling, en passant, pawn promotion, and checkmate detection, are not fully implemented.
- Piece images are downloaded from GeeksforGeeks when the game starts, so an internet connection is required.
- Background removal with `rembg` may require additional setup depending on your Python environment.

## Future Improvements

- Implement complete chess rules and checkmate detection.
- Add pawn promotion, castling, and en passant.
- Add a move history and undo functionality.
- Support playing against a computer.
- Store piece images locally to avoid downloading them every time.

## License

This project is intended for educational and personal use. Check the licenses of external images and dependencies before redistributing them.
