# 🎮 Arcade Games Hub

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-black?logo=flask)
![Pygame](https://img.shields.io/badge/Pygame-Game_Development-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

**A Python-based Arcade Games Hub that brings together three classic games—Pac-Man, Snake, and Minesweeper—under a simple Flask-powered web interface for an engaging gaming experience.**

</div>

---

# 📑 Table of Contents

- Overview
- Features
- Games Included
- Technology Stack
- System Architecture
- Project Workflow
- Project Structure
- Installation
- Usage
- Future Enhancements
- Contributing
- License
- Author

---

# 📄 Overview

Arcade Games Hub is a collection of classic arcade games integrated into a single application. The project provides a simple web interface where users can launch and enjoy popular games like **Pac-Man**, **Snake**, and **Minesweeper**.

Built using **Python**, **Flask**, and **Pygame**, the application demonstrates desktop game development integrated with a lightweight web-based launcher.

---

# ✨ Features

- 🎮 Multiple classic games in one application
- 🖥️ Simple web-based game launcher
- ⚡ Launch games with a single click
- 🐍 Classic Snake gameplay
- 👻 Pac-Man maze adventure
- 💣 Logic-based Minesweeper puzzle
- 🧩 Modular game architecture
- 🚀 Easy to extend with additional games

---

# 🎯 Games Included

## 👻 Pac-Man

Navigate through the maze, collect pellets, and avoid enemies while achieving the highest score possible.

### Features

- Classic maze gameplay
- Player movement
- Score tracking
- Enemy avoidance

---

## 🐍 Snake

Control the snake, collect food, and grow longer while avoiding collisions with walls and yourself.

### Features

- Smooth movement
- Food collection
- Increasing difficulty
- Score tracking

---

## 💣 Minesweeper

Reveal all safe cells while avoiding hidden mines using logical reasoning.

### Features

- Grid-based gameplay
- Mine detection
- Logical puzzle solving
- Win/Loss detection

---

# 🛠 Technology Stack

## Programming Language

- Python

## Backend

- Flask

## Game Development

- Pygame

## Frontend

- HTML5
- CSS3
- JavaScript

---

# 🏗️ System Architecture

```text
                User
                  │
                  ▼
          Flask Web Interface
                  │
      ┌───────────┼───────────┐
      ▼           ▼           ▼
   Pac-Man      Snake    Minesweeper
      │           │           │
      └───────────┼───────────┘
                  ▼
           Pygame Engine
```

---

# 🔄 Project Workflow

```text
Start Application
        │
        ▼
Open Web Interface
        │
        ▼
Select a Game
        │
        ▼
Launch Game
        │
        ▼
Play the Game
        │
        ▼
Exit or Choose Another Game
```

---

# 📂 Project Structure

```text
Arcade-Games-Hub/

├── app.py
├── arcade.html
├── style.css
├── pacman.py
├── snake.py
├── minesweeper.py
├── README.md
└── .gitignore
```

---

# 🚀 Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/arcade-games-hub.git

cd arcade-games-hub
```

---

## Create a Virtual Environment

```bash
python -m venv venv
```

---

## Activate the Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install flask pygame
```

Or install using:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Start the Flask server:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

Select any game from the homepage to launch it.

---

# 💻 Usage

1. Start the Flask application.
2. Open the Arcade Games Hub in your browser.
3. Choose one of the available games.
4. Click the **Play** button.
5. Enjoy the game.

---

# 🌟 Highlights

- Multiple games in a single platform
- Lightweight Flask launcher
- Interactive desktop gameplay
- Modular project structure
- Beginner-friendly implementation
- Easy to extend with additional games

---

# 🎯 Applications

- Python Game Development
- Flask Integration Projects
- Programming Practice
- Educational Demonstrations
- Desktop Entertainment
- GUI and Event Handling Practice

---

# 🔮 Future Enhancements

- Add Tetris
- Add Space Invaders
- Multiplayer support
- Global leaderboard
- User authentication
- Sound effects and background music
- Game difficulty levels
- Save high scores
- Responsive web dashboard
- Cloud deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Aditya D**

Computer Science Engineer

- 📧 Email: adityadivakar1705@gmail.com

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support helps improve the project and motivates future development.