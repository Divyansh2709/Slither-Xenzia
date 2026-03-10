# Slither-Xenzia
# 🐍 Snake Game (C++ Console)

![C++](https://img.shields.io/badge/Language-C++-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20Console-lightgrey)
![Game](https://img.shields.io/badge/Game-Terminal%20Snake-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

A **classic Snake Game** implemented using **C++ in the Windows Console**.
The game includes snake movement, growing tail mechanics, moving food, random obstacles, score tracking, and collision detection.

This project demonstrates core programming concepts such as **game loops, keyboard input handling, collision detection, and console rendering optimization**.

---

# 🎮 Game Preview

```
######################
#        o           #
#        o      F    #
#        O           #
#                    #
#    ###             #
#                    #
######################

Score: 30
Use W A S D to move
```

---

# ✨ Features

✔ Smooth console rendering (reduced flickering)

✔ Snake grows when food is eaten

✔ Randomly generated obstacles

✔ Dynamic moving food system

✔ Real-time keyboard controls

✔ Score tracking system

✔ Game-over collision detection

---

# 🎮 Controls

| Key   | Action     |
| ----- | ---------- |
| **W** | Move Up    |
| **A** | Move Left  |
| **S** | Move Down  |
| **D** | Move Right |
| **X** | Exit Game  |

---

# 🧩 Game Symbols

| Symbol | Meaning         |
| ------ | --------------- |
| `O`    | Snake Head      |
| `o`    | Snake Tail      |
| `F`    | Food            |
| `#`    | Wall / Obstacle |

---

# ⚙ Game Mechanics

* The snake **starts at the center** of the board.
* Eating food **increases the score by 10**.
* Each food eaten **increases snake length**.
* Food **moves automatically after a time interval**.
* The game ends if the snake:

  * Hits a wall
  * Hits its own tail
  * Hits an obstacle

---

# 🛠 Technologies Used

* **C++**
* **Windows Console API**
* `<conio.h>` for keyboard input
* `<windows.h>` for cursor positioning and game speed
* `<ctime>` and `<cstdlib>` for random generation

---

# 🚀 Installation & Running

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/snake-game.git
```

## 2️⃣ Navigate to the Folder

```bash
cd snake-game
```

## 3️⃣ Compile the Program

Using **g++**

```bash
g++ snakeapp.cpp -o snake
```

## 4️⃣ Run the Game

```bash
snake.exe
```

---

# 📂 Project Structure

```
snake-game
│
├── snakeapp.cpp      # Main game source code
├── README.md         # Project documentation
```

---

# 📚 Concepts Demonstrated

This project helps understand:

* Game loop architecture
* Real-time keyboard input
* Snake tail tracking using arrays
* Random generation of food and obstacles
* Collision detection logic
* Console rendering optimization

---

# 🔮 Future Improvements

Plenty of room to evolve this little terminal reptile:

* Difficulty levels (**Easy / Medium / Hard**)
* High score system
* Colored console graphics
* Pause / Resume feature
* Sound effects
* Better obstacle generation
* Cross-platform support (Linux / Mac)

---

# 👨‍💻 Contributors

**Divyansh Gupta**
**Harsh Agrahari**


---

# ⭐ Support

If you found this project helpful or interesting:

⭐ Star the repository
🍴 Fork it and improve it
🐛 Report issues or suggestions
