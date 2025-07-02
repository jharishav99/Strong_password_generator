# 🔐 Random Password Generator | C++

This is a simple **Random Password Generator** built in **C++**, where users can input a desired password length and get a randomly generated password containing uppercase, lowercase letters, and digits.

---

## 📌 Features

- Customizable password length
- Random generation using `rand()` and `time(0)`
- Uses a mix of:
  - Uppercase Letters (A–Z)
  - Lowercase Letters (a–z)
  - Digits (0–9)
- Lightweight and runs on terminal

---

## 🧠 Concepts Used

- `string` manipulation
- Random number generation (`rand()`, `srand`)
- Loops and conditionals
- Basic user input/output via `cin`, `cout`

---

## 🛠️ How to Run

1. Copy the code to a `.cpp` file (e.g., `password_generator.cpp`)
2. Compile:
   ```bash
   g++ password_generator.cpp -o password_generator
