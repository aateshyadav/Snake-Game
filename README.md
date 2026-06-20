<div align="center">

# 🐍 Snake Game

### A classic Snake game built with Python &amp; Pygame

![Python](https://img.shields.io/badge/Python-3.7%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2.x-00C853?style=for-the-badge&logo=pygame&logoColor=white)
![License](https://img.shields.io/badge/License-Free%20to%20Use-FFD700?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Playable-FF4B4B?style=for-the-badge)

</div>

---

> 🕹️ Steer the snake, gobble up food, grow longer, and try not to bite your own tail!

<div align="center">

```
 ███████████████████████████████████
 █                                  █
 █     🟩🟩🟩🟢                   █
 █              🟥                 █
 █                                 █
 █          Score: 0               █
 ███████████████████████████████████
```

*(Add your own gameplay screenshot or GIF here — e.g. `![gameplay](screenshot.png)`)*

</div>

---

## ✨ Features

| | |
|---|---|
| 🟩 | Smooth grid-based movement on a 20×20 board |
| 🏆 | Live score tracking displayed on screen |
| 💀 | Game over screen with restart/quit options |
| 🍎 | Randomly spawning food that avoids the snake's body |

---

## 📋 Requirements

- 🐍 Python 3.7+
- 🎮 Pygame

---

## ⚙️ Installation

**1.** Make sure Python is installed on your system.

**2.** Install Pygame:

```bash
pip install pygame
```

---

## ▶️ How to Run

Run the game script from your terminal:

```bash
python snake_game.py
```

> 💡 Replace `snake_game.py` with the actual filename if different.

---

## 🎮 Controls

| Key | Action |
|:---:|---|
| ⬆️ `Arrow Up` | Move up |
| ⬇️ `Arrow Down` | Move down |
| ⬅️ `Arrow Left` | Move left |
| ➡️ `Arrow Right` | Move right |
| 🔄 `R` | Restart game |
| ❌ `Q` | Quit game |

---

## 📜 Gameplay Rules

- 🕹️ Use the arrow keys to steer the snake around the board.
- 🍎 Eating the red food block increases your score by **+1** and grows the snake by one segment.
- 💥 The game ends if the snake hits a wall or collides with its own body.
- 🔁 On the Game Over screen, press **R** to restart or **Q** to quit.

---

## 🛠️ Configuration

Tweak the game's behavior by editing the constants at the top of the script:

| Constant | Description | Default |
|---|---|:---:|
| `CELL_SIZE` | Size of each grid cell in pixels | `20` |
| `GRID_WIDTH` | Number of cells horizontally | `20` |
| `GRID_HEIGHT` | Number of cells vertically | `20` |
| `FPS` | Game speed (frames per second) | `10` |

---

## 🎨 Color Palette

| Color | Used For |
|---|---|
| 🟢 Green | Snake body |
| 🟢 Dark Green | Snake head |
| 🔴 Red | Food |
| ⚫ Black | Background |
| ⬜ Gray | Grid lines |
| ⬜ White | Score text |

---

## 📄 License

🆓 Free to use and modify for personal or educational purposes.

<div align="center">

Made with 🐍 + 🎮 + ❤️

</div>
