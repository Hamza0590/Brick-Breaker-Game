# 🎮 Arkadriod Brick Breaker Game

A modern C++ implementation of the classic brick breaker arcade game.

## 🧠 Objective

The primary goal of this project is to apply Object-Oriented Programming (OOP) principles such as **encapsulation**, **inheritance**, **polymorphism**, and **abstraction** by building a feature-rich version of the Brick Breaker game.

## 🕹️ Game Overview

Arkadriod challenges players to break bricks using a bouncing ball and a paddle they control. The game features:

- 🎯 Multiple levels with increasing difficulty
- 🧱 Variety of bricks with different durability
- ⚡ Power-ups and power-downs
- 🎨 Interactive visuals and score tracking
- 🧠 Logic-driven OOP architecture

Play the reference version of the game here: [https://poki.com/en/g/brick-breaker](https://poki.com/en/g/brick-breaker)

---

## 🧩 Key Features

### 🔄 Paddle Control
- Bottom Paddle: Controlled via **mouse**
- Upper Paddle (Level 3): Controlled via **keyboard (W & R)**

### 🧱 Bricks
Each level contains different types of bricks:
- **Green**: Breaks in 1 hit
- **Pink**: Breaks in 2 hits
- **Blue**: Breaks in 3 hits
- **Red**: Breaks in 3 hits
- **Yellow**: Breaks in 2 hits

### 🔮 Power-Ups and Power-Downs
| Power Type | Shape      | Effect                                 |
|------------|------------|----------------------------------------|
| Green      | Triangle   | Increases paddle size (double)         |
| Pink       | Square     | Decreases paddle size (half)           |
| Blue       | Circle     | Slows down ball for 5 seconds          |
| Red        | Rectangle  | Speeds up ball for 5 seconds           |
| Yellow     | Square     | Adds 2 extra balls for 5 seconds       |

### 🎯 Scoring
Points awarded for each brick destroyed. High scores are stored using **file handling** with player names.

### 📊 Game Levels
- **Level 1**: Rectangle brick pattern
- **Level 2**: Custom complex pattern
- **Level 3**:
  - Recursive brick pattern
  - Dual paddles (mouse & keyboard control)
  - Power-ups affect both paddles

### ❤️ Lives and Game Over
- 2 lives per level
- Game ends if ball falls from **any** paddle (Level 3)

## 🧪 Technical Details

### 🧱 Essential Classes
- `Brick`
- `Ball`
- `Paddle`
- `Food` (for Power-Ups)

## 💡 Bonus Features
- Ball changes color to match brick it hits
- Paddle changes color to match ball after collision
- Score and Roll number shown on canvas
- 
---

## 🧑‍💻 Development

- **Language**: C++
- **Tools**: OpenGL / GLUT
- **Environment**: Ubuntu / Visual Studio / Eclipse

---

## 📜 License

This project is for academic purposes only.

