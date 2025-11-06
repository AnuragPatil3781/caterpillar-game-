# caterpillar-game-
Caterpillar is a fast, lightweight arcade game written in Python that recreates the classic snake/caterpillar gameplay with smooth controls, increasing difficulty, and polished visuals.
The player maneuvers a growing caterpillar to eat food items while avoiding collisions with walls and its own body; as the score increases, game speed and challenge ramps up, making quick reflexes and strategies essential. Built for learning and fun, this project demonstrates game-loop architecture, sprite management, collision detection, and simple state-driven UI in a clean, well-documented codebase suitable for beginners and portfolio use.

Key features

Smooth, frame-rate–friendly game loop and responsive controls (keyboard arrow keys / WASD).

Dynamic growth mechanics: caterpillar length increases when eating food; new obstacles and power-ups spawn at later levels.

Score, high-score persistence (local file), pause/resume, and restart functionality.

Simple but attractive UI with sprites, animations, and sound effects (optional).

Modular code structure: game.py (main loop), player.py (caterpillar logic), food.py, ui.py, settings.py — easy to extend.

Unit-testable components for core logic (movement, collision, scoring) and clear inline documentation.

Tech stack

Language: Python 3.8+

Libraries: pygame for rendering and input; optionally numpy for grid math (not required).

Platform: Cross-platform (Windows / macOS / Linux).

Why this project is useful (for a portfolio / CV)

Demonstrates practical knowledge of real-time programming concepts: event loops, frame timing, and input handling.

Shows ability to design modular, testable code and create polished user-facing applications.

Combines algorithmic thinking (collision detection, path constraints) with UX polish (menus, sound, smooth animation).

Installation & quickstart

Clone the repository:

git clone https://github.com/<AnuragPatil3781>/caterpillar.git
cd caterpillar


Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt


Run the game:

python game.py

Controls

Arrow keys or W A S D — move caterpillar

P — pause / resume

R — restart game

Esc or close window — quit

Project structure (example)
caterpillar/
├─ game.py           # entry point and main loop
├─ player.py         # caterpillar movement, growth, collision logic
├─ food.py           # food spawning and power-ups
├─ ui.py             # menu, score display, high-score persistence
├─ assets/           # images, sprites, sound files
├─ tests/            # unit tests for game logic
└─ README.md

Extensibility ideas

Add AI-controlled caterpillar/bots for single-player competition or local multiplayer.

Port to mobile with touch controls using Kivy or Pygame Subset for Android.

Implement level editor and custom obstacle maps.

Networked multiplayer mode (competitive or cooperative).

Contribution

Contributions welcome: open issues for bugs, feature requests, or improvements. Follow the repo's code style and include unit tests for new logic.

License

MIT License — free to use, modify, and distribute (see LICENSE).

Three-line CV blurb (ready-to-use)

Developed Caterpillar, a Python-based arcade game using pygame that implements smooth real-time controls, modular game-loop architecture, and persistent high-score saving.

Built features including dynamic caterpillar growth, collision detection, pause/resume, and increasing difficulty mechanics; structured into testable modules for movement, spawning, and UI.

Project demonstrates practical skills in event-driven programming, game design, and clean code—suitable for inclusion in a programming portfolio or GitHub showcase.
