# 🃏 Blackjack Showdown (User vs CPU)

A simple Unity-based 2D blackjack game where a player (User) competes against a CPU (dealer). The game mimics core blackjack rules with visual card sprites, user input for actions, and dynamic score tracking.

---

## 🎮 How to Play

- You begin with **2 cards**, and so does the CPU.
- Press `H` to **Hit** (draw another card).
- Press `S` to **Stay** (end your turn and reveal CPU's full hand).
- The CPU draws until it reaches **at least 16 points**.
- Press `R` to **Reset** the game and start a new round.

The game keeps track of how many rounds you win vs. how many the CPU wins!

---

## 🧠 Game Rules

- Cards are worth values between 1 and 10.
- If your hand goes over 21, **you bust** and lose.
- If you stay and the CPU's total is lower than yours (or it busts), **you win**.
- If the CPU has a higher total (≤21), **you lose**.

---

## 🔧 Features

- Dynamic card spawning with **card sprites**
- CPU cards partially **face-down** until revealed
- Score tracking: `CPU Wins vs You`
- Reset option with keypress
- Simple UI using **TextMeshPro**

---

## 🛠️ Controls

| Key | Action         |
|-----|----------------|
| H   | Hit (draw a card) |
| S   | Stay (end turn) |
| R   | Reset game      |

---

## 💡 Future Improvements (Ideas)
- Add Ace logic (1 or 11)
- Multiplayer support
- Animations for card flip/draw
- Chip betting system
- Background music / sound effects

---

## 📁 Project Structure

