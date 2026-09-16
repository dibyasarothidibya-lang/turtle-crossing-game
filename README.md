# 🐢 Turtle Crossing Game (Frogger Arcade)

A classic Frogger-inspired arcade game built in Python using Object-Oriented Programming (OOP) and the built-in `turtle` graphics library.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Library](https://img.shields.io/badge/GUI-Turtle%20Graphics-brightgreen)
![Paradigm](https://img.shields.io/badge/Architecture-OOP-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🎮 Game Overview

Control the turtle and safely navigate across a busy highway packed with oncoming, colorful traffic! 
Reach the top to level up while the traffic speeds up, but be careful—a single collision with a car ends the game.

---

## ✨ Features

- **Turtle Navigation**: Responsive movement controls to navigate north across the highway.
- **Dynamic Traffic System**: Colorful cars (`CarManager`) spawn at random vertical lanes and move across the screen from right to left.
- **Collision Detection**: Real-time bounding box / distance detection between the turtle and passing vehicles.
- **Object-Oriented Design**: Clean modular code separated into dedicated classes:
  - `Player` ([player.py](player.py))
  - `CarManager` ([car_manager.py](car_manager.py))
  - `Scoreboard` ([scoreboard.py](scoreboard.py))
- **Zero Third-Party Dependencies**: Runs directly using Python's standard library.

---

## 🕹️ Controls

| Action | Key |
| :--- | :---: |
| **Move Up / Forward** | <kbd>▲ Up Arrow</kbd> |

---

## 📋 Prerequisites

- **Python 3.6+** installed on your system.
*(No `pip install` commands required — `turtle`, `time`, and `random` are built into Python!)*

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dibyasarothidibya-lang/turtle-crossing-game.git
   cd turtle-crossing-game
   ```

2. **Run the game:**
   ```bash
   python main.py
   ```

---

## 📁 Project Structure

```text
├── main.py            # Main game loop, screen setup, and event listening
├── player.py          # Player turtle class and movement logic
├── car_manager.py     # Car generation, randomization, and movement mechanics
├── scoreboard.py      # Score tracking and game over display
├── .gitignore         # Ignores __pycache__ and bytecode
└── README.md          # Project documentation
```

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to add new features (e.g. left/right movement, sound effects, power-ups, or high-score tracking), feel free to fork the repository and submit a PR.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
