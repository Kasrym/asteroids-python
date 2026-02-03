# Asteroids (Python)

A classic **Asteroids‑style arcade game** built in Python — a fun project showcasing game loop logic, object movement, input handling, shooting mechanics, and collision detection. Inspired by traditional arcade gameplay and implemented using Python.

## 🎮 Overview

In this game you control a spaceship that must avoid and destroy asteroids while navigating space. The game demonstrates:

- Player movement and rotation
- Projectile shooting
- Asteroid spawning and collision detection
- Game loop and event handling
- Simple physics‑based motion

## 🛠️ Technologies

- **Python 3.x**
- **Pygame** 
- Modular Python files for organization

## 📁 Project Structure
.
├── asteroid.py
├── asteroidfield.py
├── player.py
├── shot.py
├── constants.py
├── logger.py
├── main.py
├── pyproject.toml
└── README.md

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Kasrym/asteroids-python.git
cd asteroids-python
```

### 2. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

```bash
pip install pygame
python main.py
```
## 🎯 Gameplay
	•	Use arrow keys or WASD to move/rotate your ship
	•	Press a key Space to shoot
	•	Avoid or destroy asteroids to live
	•	Game ends if your ship collides with an asteroid

