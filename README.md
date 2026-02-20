# 🚀 Asteroids Game (Pygame)

A classic Asteroids-style arcade game built using Python and Pygame.

## 🎮 Features

- Player movement with rotation and thrust
- Shooting with cooldown system
- Asteroid collision detection
- Asteroid splitting mechanics:
  - Large → 2 Medium
  - Medium → 2 Small
  - Small → Destroyed
- Split asteroids move faster
- Randomized split angles (20–50 degrees)
- Event logging system

## 🛠 Tech Stack

- Python 3
- Pygame

## ▶️ How to Run

1. Install dependencies (if not already installed):
   ```bash
   uv sync
   ```

2. Run the game:
   ```bash
   uv run main.py
   ```


## 🎯 Controls

- `A` – Rotate Left  
- `D` – Rotate Right  
- `W` – Move Forward  
- `S` – Move Backward  
- `SPACE` – Shoot  

## 📂 Project Structure

```
.
├── main.py
├── player.py
├── asteroid.py
├── circleshape.py
├── constants.py
├── logger.py
└── game_events.jsonl
```

## 📌 Learning Goals

This project demonstrates:

- Object-Oriented Programming
- Inheritance
- Vector math with Pygame
- Game loops & delta time
- Collision handling
- Cooldown timers
- Event logging
- Clean game architecture

---

Built as a learning project to understand game mechanics and OOP design.
