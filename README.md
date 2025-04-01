
# 🚢 Battleship - Terminal Game in Python

This project is a Python implementation of the classic **Battleship** game. It allows a human player to play against a simple computer opponent in a terminal-based interface.

## 🎮 Features

- Fully playable via the terminal.
- Human vs. AI gameplay.
- Manual or random ship placement.
- Real-time board updates and feedback (Hit, Miss, Sunk).
- Endgame detection with winner announcement.
- Basic AI that attacks random coordinates.

## 🧱 Game Structure

- **Casella**: Represents each cell on the board.
- **Taulell**: The game board; handles ship placement and game logic.
- **Jugador**: The human player class.
- **JugadorMaquina**: The computer player with basic attack logic.
- **Partida**: Manages the full game loop and interaction between players.

## ▶️ How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/battleship-game.git
   cd battleship-game
   ```

2. Run the game:
   ```bash
   python Battleship.py
   ```

3. Follow the prompts in the terminal to place ships and attack enemy coordinates.

## ⚠️ Requirements

- Python 3.6+
- No external libraries required (only `random`, `os`, and `multiprocessing` from standard library)

## 📷 Preview

Here's what the board looks like during gameplay (example output):

```
     0 | 1 | 2 | 3 | 4 | 5 | 6 | 7
 A | A | A | f | f | f | f | A | A
 B | A | A | A | A | A | A | A | A
 C | A | A | A | A | A | A | A | A
 ...
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
