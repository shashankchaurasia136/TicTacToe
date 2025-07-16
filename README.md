# 🎮 3D Aesthetic Tic-Tac-Toe

> ✨ A visually appealing, animated 3D Tic-Tac-Toe game using only HTML, CSS, and JavaScript.  
> 🧠 Built as **Task 1** for the **Prodigy Infotech Web Development Internship Program**.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How the Game Works](#how-the-game-works)
- [Setup Instructions](#setup-instructions)
- [Live Demo](#live-demo)
- [Learning Outcomes](#learning-outcomes)
- [Task Details](#task-details)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## 📖 About the Project

This is a creative twist on the classic **Tic-Tac-Toe** game with a modern 3D glassmorphism interface. The goal was to build an **interactive, responsive, and aesthetic** mini-game with minimal code complexity using only front-end tools.

It features glowing animations, 3D hover effects, and turn-based logic, making it both a design and logic-based project — ideal to demonstrate core frontend skills.

---

## ✨ Features

- 🎨 **Modern Aesthetic UI** with gradients, glass blur, and neon effects
- 📲 **Responsive Design** for both desktop and mobile screens
- 🔁 **Turn-Based Logic** (X starts first)
- ✅ **Win Detection** and 🟰 **Draw Detection**
- 🌀 **Animated Symbols** with glowing shadows and scale effects
- ♻️ **Restart Button** to reset the board instantly
- 🎯 Easy-to-understand **game logic** using vanilla JavaScript

---

## 🧱 Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5      | Page structure |
| CSS3       | Styling, animation, and 3D effects |
| JavaScript | Game mechanics, event handling, win/draw logic |

---

## 🧠 How the Game Works

- The game board is a 3x3 grid.
- Two players take turns to place `X` and `O` alternately.
- The first player to place 3 of their marks in a horizontal, vertical, or diagonal row wins.
- If all 9 cells are filled without a winner, the game ends in a draw.
- The game can be reset at any time using the "Restart Game" button.

### 🎯 Winning Combinations

```js
const winningCombinations = [
  [0,1,2], [3,4,5], [6,7,8], // rows
  [0,3,6], [1,4,7], [2,5,8], // columns
  [0,4,8], [2,4,6]           // diagonals
];
