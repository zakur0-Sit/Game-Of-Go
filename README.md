# The Game of Go

This project implements the classic board game **Go**, developed in Python using **Pygame**.  
It allows players to compete in either **1-player (vs computer)** or **2-player** mode, on different board sizes (9x9, 13x13, 19x19).  
The game automatically calculates the score based on captured stones and territory control.

( ͡° ͜ʖ ͡°)

---

## Overview

**The Game of Go** recreates the elegance and complexity of one of the world's oldest strategy games.  
Players take turns placing stones on the board to claim territory, capture enemy stones, and outsmart their opponent.  
The project features a complete graphical interface, background music, and realistic gameplay logic.

---

## Features

- Three board sizes: **9×9**, **13×13**, and **19×19**
- Single-player (against computer) and two-player modes
- Automatic score calculation (territory + captures)
- Background music and sound effects
- Resizable graphical interface
- Endgame menu with Replay, Main Menu, and Quit options

---

## Requirements

- Python 3.9 or later
- Pygame library

Install dependencies with:
```bash
pip install pygame
```

---

## How to Run

Ensure the following structure exists:

```
main.py
fonts/
 ├── Japan Daisuki.otf
 └── futura.otf
images/
 ├── bg1.jpg
 ├── bg2.jpg
 ├── bg3.png
 └── go.png
sounds/
 ├── bg.wav
 ├── put.wav
 └── decline.ogg
```

Then start the game with:
```bash
python main.py
```

---

## Controls

- **Left Click** — Place a stone  
- **P** — Pass your turn  
- After **two consecutive passes**, the game ends and scores are displayed  

At the end screen you can choose:
- Replay the game  
- Return to the main menu  
- Quit the program  

---

## Game Rules (summary)

- The goal is to control the largest area of the board.  
- Stones are captured when they lose all liberties (empty adjacent points).  
- Empty regions completely surrounded by stones of one color count as that player’s territory.  
- The game ends when both players pass. The player with the higher score wins.  

---

## Technical Details

- **Language:** Python 3  
- **Graphics:** Pygame  
- **Sound:** `.wav` and `.ogg` formats  
- **Font:** "Japan Daisuki" (stylized Japanese font)  
- **Interface:** Dynamic and resizable window  

---

## Author

Developed by **zakur0-Sit**  
GitHub: [https://github.com/zakur0-Sit](https://github.com/zakur0-Sit)

This project was created for educational and recreational purposes, showcasing how to implement complex board logic in an interactive graphical environment.

---

## License

Released under the **MIT License**.  
You are free to use, modify, and distribute this code with proper attribution.

---

(╯°□°）╯︵ ┻━┻   — *A simple game... yet endless depth.*
