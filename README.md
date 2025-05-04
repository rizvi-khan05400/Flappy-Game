# Flappy-Game
# 🐦 Flappy Bird Game - Python (Pygame)

A Python implementation of the classic Flappy Bird game using the [Pygame](https://www.pygame.org/) library.

![Flappy Bird Screenshot](assets/preview.png)

## 🚀 Features

- Classic Flappy Bird gameplay
- Smooth animations and game physics
- Score tracking
- Game over and restart functionality
- Modular OOP design (Bird, Pipe, Base)

## 📁 Project Structure

flappy-bird/
├── assets/
│ ├── bird1.png
│ ├── bird2.png
│ ├── bird3.png
│ ├── pipe.png
│ ├── base.png
│ ├── bg.png
│ └── GameOver.Png
├── flappy_game.py
├── README.md
└── flappy_bird_code_explained.pdf


## 🛠 Requirements

- Python 3.6+
- Pygame

Install dependencies:

```bash
pip install pygame

python flappy_game.py

🎮 Controls
    1.Press SPACEBAR to make the bird jump

    2.Avoid pipes and don’t fall to the ground

    3.Score increases every time you pass a pipe

📸 Screenshots
(Place screenshots in the assets/ folder and link here if needed)

🧠 Code Structure
    1.Bird: Handles bird physics, animation, rotation

    2.Pipe: Generates pipes, moves them, detects collision

    3.Base: Scrolling ground effect

    4.draw_window(): Renders all game objects

    5.main(): Main game loop

    6.game_over(): Game over screen

📄 Documentation
See flappy_bird_code_explained.pdf for a line-by-line code explanation.
