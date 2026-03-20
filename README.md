# 🐍 Rattle Snake Game (C++ Graphics)

A classic **Snake Game built in C++ using graphics.h**, featuring real-time movement, collision detection, scoring system, and persistent high score storage.

---

## 📌 Overview

This project recreates the classic Snake (Rattle Snake) game using **Turbo C++ graphics mode**. It demonstrates low-level graphics handling, keyboard interaction, and game loop mechanics.

---

## 🚀 Features

### 🎮 Gameplay
- Real-time snake movement
- Directional controls (Up, Down, Left, Right)
- Food consumption increases score and snake length
- Game over on:
  - Self collision
  - Wall collision (maze mode)

### 🧠 Game Mechanics
- Dynamic snake growth
- Collision detection (body + boundary)
- Random food generation
- Speed control via delay

### 🏆 Scoring System
- Live score tracking
- Persistent **high score system** using file storage
- High score updates automatically

### 🎨 Graphics
- Built using `graphics.h` (BGI)
- Custom rendering for:
  - Snake head (direction-based)
  - Body segments
  - Tail variations
  - Food
- Sidebar UI:
  - Instructions
  - Score
  - High score
  - Player info

---

## 🎯 Controls

| Action       | Key |
|-------------|----|
| Move Up     | `8` |
| Move Down   | `5` |
| Move Right  | `6` |
| Move Left   | `4` |
| Exit Game   | `0` |

---

## 🧠 Gameplay Flow
Game starts →
Snake initialized →
Player input controls movement →
Food appears randomly →
Snake eats food → grows + score increases →
Collision detection →
Game over → score saved


---

## 🗂️ File Usage

| File Path                  | Purpose |
|---------------------------|--------|
| `c:\tc\bin\rattle.txt`    | Stores high score |

---

## 🛠️ Tech Stack

- **Language:** C++
- **Graphics Library:** `graphics.h` (BGI)
- **Concepts Used:**
  - Game loop
  - Collision detection
  - File handling (`fstream`)
  - Dynamic memory (`malloc`, `free`)
  - Keyboard input (`conio.h`)

---

## ▶️ How to Run

### ✅ Recommended: Turbo C++ / DOSBox

1. Install Turbo C++ or DOSBox
2. Place the file in: C:\Turboc3\BIN
3. Ensure BGI drivers exist at: C:\Turboc3\BGI

4. Compile and run

---

### ⚠️ Important Notes

- Requires legacy headers:
- `graphics.h`
- `conio.h`
- `dos.h`
- Will **NOT run on modern compilers (GCC/Clang)** without modification

---

## ⚠️ Limitations

- Hardcoded file paths (`C:\tc\bin\`)
- Uses outdated graphics library
- No modular architecture
- Fixed resolution dependency
- Keyboard input is blocking

---

## 💡 Future Improvements

- Migrate to modern graphics:
- SDL / SFML / OpenGL
- Replace `graphics.h` with cross-platform library
- Add levels & difficulty scaling
- Add pause/resume feature
- Store scores in database or JSON
- Build web or mobile version

---

## 📸 Game UI Sections

- 🕹️ Game Area (Snake movement)
- 📘 Instructions Panel
- 📊 Score & High Score Display
- 🧱 Maze Boundaries

---

## 📈 Learning Outcomes

- Understanding of **game loops**
- Real-time input handling
- Basic **2D graphics rendering**
- Collision detection logic
- File-based persistence

---

## 🤝 Contribution

Improvements are welcome:
- Refactor into modular code
- Replace legacy dependencies
- Add animations & sound enhancements
- Optimize rendering

---

## 📄 License

This project is for educational purposes
