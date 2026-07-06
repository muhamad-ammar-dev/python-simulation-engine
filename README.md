# 🚀 Python Event-Driven Simulation Engine

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Architecture](https://img.shields.io/badge/Architecture-Event--Driven-purple)
![License](https://img.shields.io/badge/License-MIT-orange)

## 📌 Engine Overview
An object-oriented, event-driven simulation platform built with Python's Turtle graphics. This engine manages asynchronous user-input listening, vector-based kinematic calculations, and continuous execution loops within a localized coordinates environment.

## ✨ Core Features
- 🕹️ **Event-Driven Input Listening:** Asynchronous keyboard event hooks (`W/S` and `Arrow Keys`) for dual-player execution.
- ⚡ **Kinematic Acceleration:** Progressive velocity vector updates upon successful entity collision.
- 📊 **State & Score Tracking:** Real-time state validation with an automated first-to-7 termination threshold.
- 🎨 **Procedural Layout Rendering:** Object positioning and clean visual output driven by Turtle graphics API.
- 🎯 **Rigid Body Reflected Mechanics:** Algorithmic boundary checking for precise collision detection and vector resets.

## 🛠️ Technical Implementation

### 🧱 Modular Components
The engine architecture isolates individual entities into domain-specific modules:

```python
# System Core Architecture
from turtle import Turtle, Screen
from paddle import Paddle
from ball import Ball
from scoreboard import Scoreboard
```

### 🧬 Class Architecture
1. **Paddle Class** - Player-controlled subsystems managing directional movement vectors.
2. **Ball Class** - Dynamic simulation object managing position coordinates and collision kinematics.
3. **Scoreboard Class** - State monitoring system handling numeric score data and terminal rendering.

## 📦 System Requirements
- Python 3.8+
- Turtle module (Standard library dependency)

## ⚙️ Installation & Execution

```bash
git clone https://github.com/muhamad-ammar-dev/python-simulation-engine.git
cd python-simulation-engine
python ping_pong.py
```

## 🎮 Simulation Control Layout

| Entity Cluster | Input Vector Keys |
|----------------|-------------------|
| Left Actuator | `W` (Up), `S` (Down) |
| Right Actuator | `↑` (Up), `↓` (Down) |

## 📊 Scoring & Termination Criteria
- The system terminates and reaches the victory condition when a single instance scores 7 points.
- The ball object executes a coordinate reset after each point validation.
- Progressive velocity vector acceleration is applied to increase difficulty.

## 🖥️ System Interface Preview

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

## 📂 Project Structure

```text
python-simulation-engine/
├── ping_pong.py       # Main engine execution & event loop
├── paddle.py          # Paddle class implementation
├── ball.py            # Ball physics and vector updates
├── scoreboard.py      # Score tracking and text rendering
└── README.md          # System documentation
```

## 🤝 Contributing Guidelines
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 📜 License
MIT License - See [LICENSE](LICENSE) for details.

## 📧 Engineering Contact
- ✉️ **Email**: [muhamedammar0900@gmail.com](mailto:muhamedammar0900@gmail.com)
- 🔗 **LinkedIn**: [Muhamad Ammar](https://www.linkedin.com/in/muhamad-ammar-18b427306)

---

For bug reports or feature requests, please open an issue on GitHub.

## 🏆 Victory Condition
First player to score 7 points wins the match execution with a terminal **"GAME OVER"** screen render!
