
# 🎯 Number Guessing Game (C++)

This is a fun **Number Guessing Game** built with C++. It challenges the player to guess a randomly generated number within a limited number of attempts, based on difficulty level.

---

## 🎮 Game Features

- Levels of difficulty:
  - 🟢 **Easy**: Guess between 0 and 10 (3 chances)
  - 🟡 **Medium**: Guess between 0 and 50 (10 chances)
  - 🔴 **Hard**: Guess between 0 and 100 (20 chances)
- Random number generation using `rand()` and `time()`
- Tracks chances left and gives hints (too high or too low)
- Validates input ranges for each level
- Clear instructions and feedback messages

---

## 🛠️ Tech Used

- **C++**
- Windows Console (requires `windows.h`)
- Random number generation with `srand()` and `rand()`
- Standard I/O: `iostream`, `cin`, `cout`

---

## 🚀 How to Run

### 📌 Prerequisites
- Windows OS
- C++ compiler that supports `windows.h` (e.g., MinGW)

### ▶️ Compile and Run

```bash
g++ -o guessing_game guessing_game.cpp
./guessing_game
```

---

## 🧠 How to Play

1. Enter your name.
2. Choose a difficulty level:
   - Easy: 0–10
   - Medium: 0–50
   - Hard: 0–100
3. Try to guess the number in the limited number of chances.
4. The game gives hints if your guess is too high or too low.
5. Win by guessing correctly or lose if you run out of chances.

---

## ⚠️ Input Rules

- Input **must** be a number within the range of the selected difficulty.
- Invalid inputs still consume a chance.
- The game is fully text-based and runs in the terminal.

---

## 📸 Demo

```
====================  Welcome Number Guess Game ====================
Enter Your Name :- Chief

Enter the Level
1. Easy (0 to 10)
2. Mid (0 to 50)
3. Hard (0 to 100) :- 2

====== Now You Have only 10 chances to guess =====
Enter the number : 34
Good but Not perfect guess... Your guess number is small...

...
```

---

## 💡 Possible Improvements

- Add a scoring system
- Implement retry or replay feature
- Make cross-platform (remove `windows.h`)
- Add GUI using C++ libraries like SFML or Qt

---

## 👨‍💻 Author

- **Vaishnavi** 

---

