# 🎮 CodeAlpha Hangman Game

## 📌 Project Description
A simple text-based Hangman game built in Python for the CodeAlpha Internship. The program selects a random word from a predefined list and lets the player guess letters with a maximum of 6 wrong attempts. It demonstrates Python basics including loops, conditionals, lists, strings, and the random module.

---

## ⚡ Features
- Predefined word list of 5 words (`python`, `flask`, `numpy`, `pandas`, `script`)
- Random word selection
- Tracks correct and incorrect guesses
- Limits incorrect attempts to 6
- Console-based input/output
- Win/Loss messages displayed at the end

---

## 🛠️ Technologies Used
- **Python 3**
- Built-in modules (`random`)
- Core concepts: loops, conditionals, lists, strings

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CodeAlpha_HangmanGame.git
2. Navigate to the project folder:
   cd CodeAlpha_HangmanGame
3. Run the game:
   python hangman.py

🧪 Sample Test Cases- Case 1 (Win): Input letters p, y, t, h, o, n → Output: You win! The word was python
- Case 2 (Loss): Input letters z, x, q, w, e, r → Output: Game Over! The word was flask
- Case 3 (Mixed): Input letters n, a, u, m, z, p, y → Output: You win! The word was numpy
- Case 4 (Repeat Guess): Input letters p, p, a, n, d, s → Output: You already guessed that letter → You win! The word was pandas
- Case 5 (Invalid Input): Input 12, @, sc → Output: Please enter a single alphabet letter



   
