## Asteroids
A classic Asteroids arcade game built with Python and Pygame.

# Requirements
- Python 3.13+
- Pygame

# Installation
git clone https://github.com/Vi1trumite/Asteroids.git
cd Asteroids
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install pygame

# Running the Game
- python main.py

# Controls
Key        Action
---------  ----------------
W          Thrust forward
S          Thrust backward
A          Rotate left
D          Rotate right
Space      Shoot

# Gameplay
- Survive as long as possible by shooting asteroids before they hit you. Large asteroids split into two smaller, faster ones when shot. The game ends when an asteroid collides with your ship.

# Project Structure
File                Description
------------------  -----------------------------------------
- main.py           Game loop and entry point
- player.py         Player ship logic and controls
- asteroid.py       Asteroid behavior and splitting
- asteroidfield.py  Asteroid spawning system
- shot.py           Projectile logic
- circleshape.py    Base class for circular game objects
- constants.py      Game configuration values
- logger.py         Debug logging utilities
