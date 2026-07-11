# 🏓 Python Event-Driven Ping Pong Game

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Architecture](https://img.shields.io/badge/Architecture-Event--Driven-purple)
![License](https://img.shields.io/badge/License-MIT-orange)

## 📌 Game Overview

An object-oriented Ping Pong game built with Python's Turtle graphics, showcasing **event-driven programming**, **collision detection**, **modular architecture**, and **real-time game state management**. The game features responsive keyboard controls, dynamic ball movement, progressive speed, and an automatic victory condition.

---

## ✨ Core Features

- 🕹️ **Event-Driven Input Handling** – Responsive keyboard event listeners (`W`, `S`, `↑`, `↓`) for smooth two-player gameplay.
- ⚡ **Progressive Ball Speed** – The ball accelerates after each successful paddle collision, increasing gameplay difficulty.
- 🎯 **Collision Detection** – Accurate collision handling between the ball, paddles, and screen boundaries.
- 📊 **Real-Time Score Tracking** – Live score updates with automatic victory detection after reaching seven points.
- 🧩 **Modular Object-Oriented Design** – Independent classes for paddles, ball behavior, and scoreboard management.
- 🎨 **Turtle Graphics Rendering** – Lightweight graphical interface powered by Python's built-in Turtle module.

---

## 🛠️ Technical Implementation

### 🧱 Modular Architecture

The project follows a modular object-oriented architecture where each game component is encapsulated within its own module.

```python
from turtle import Turtle, Screen
from paddle import Paddle
from ball import Ball
from score import Scoreboard
```

### 🧬 Class Responsibilities

| Class | Responsibility |
|-------|----------------|
| **Paddle** | Handles player movement and paddle positioning. |
| **Ball** | Controls movement, collision detection, speed progression, and reset logic. |
| **Scoreboard** | Manages score rendering, victory detection, and game-over display. |

---

## 📦 System Requirements

- Python 3.8+
- Turtle (Python Standard Library)

---

## ⚙️ Installation & Execution

```bash
git clone https://github.com/muhamad-ammar-dev/ping-pong-game.git

cd ping-pong-game

python ping_pong.py
```

---

## 🎮 Controls

| Player | Controls |
|--------|----------|
| Left Paddle | `W` (Move Up) / `S` (Move Down) |
| Right Paddle | `↑` (Move Up) / `↓` (Move Down) |

---

## 📊 Gameplay Mechanics

- The ball bounces off paddles and screen boundaries.
- Ball speed progressively increases after successful paddle collisions.
- The ball automatically resets to the center after each point.
- The first player to score **7 points** wins the match.
- A **GAME OVER** screen is displayed when the match ends.

---

## 🖥️ Interface Preview

```text
    Left: 3   |   Right: 5
    -------------------------
    |                       |
    |   |               |   |
    |   |       ○       |   |
    |   |               |   |
    |                       |
    -------------------------
```

---

## 📂 Project Structure

```text
ping-pong-game/
│
├── ping_pong.py      # Main game loop
├── paddle.py         # Paddle implementation
├── ball.py           # Ball movement & collision logic
├── score.py          # Score management and game-over display
└── README.md
```

---

## 🚀 Technologies Used

- Python
- Object-Oriented Programming (OOP)
- Event-Driven Programming
- Turtle Graphics
- Algorithms
- Collision Detection


---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 📧 Contact

- 📩 **Email:** [Muhamedammar0900@gmail.com](mailto:Muhamedammar0900@gmail.com)
- 💼 **LinkedIn:** [Muhamad Ammar](https://www.linkedin.com/in/muhamad-ammar-18b427306)

