# 🎲 Craps – Python Dice Game

A simple command-line implementation of the classic Craps casino dice game written in Python. This project simulates the basic Pass Line rules using random dice rolls.

---

## 📌 About the Game

Craps is a dice game where players roll two dice and win or lose based on the total rolled.

### 🟢 Come-Out Roll (First Roll)

- **Win immediately** if you roll:
  - `7` or `11`
- **Lose immediately** if you roll:
  - `2`, `3`, or `12`
- If you roll:
  - `4, 5, 6, 8, 9, or 10`
  
  That number becomes your **Point**.

---

### 🔁 Point Phase

- Keep rolling the dice.
- **Win** if you roll your Point again.
- **Lose** if you roll a `7` before hitting your Point.

---
