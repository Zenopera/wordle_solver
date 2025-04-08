# 🧠 Wordle Solver Assistant

This project is an interactive Python-based assistant that helps you solve the popular game [Wordle](https://www.nytimes.com/games/wordle/index.html) (also playable at [wordly.org](https://wordly.org/)).

It analyzes your feedback from each guess and intelligently suggests the next word to try, guiding you to find the solution in 6 attempts or fewer.

---

## 🎮 What is Wordle?

Wordle is a word puzzle game where you have 6 attempts to guess a secret 5-letter English word.

After each guess, you're given feedback for each letter:
- 🟩 **Green (G)** – the letter is correct and in the correct position.
- 🟨 **Yellow (Y)** – the letter is in the word but in the wrong position.
- ⬜ **Gray (B)** – the letter is not in the word at all.

Your goal is to use this feedback to progressively narrow down the possibilities and guess the correct word.

You can play Wordle here:
- [New York Times version](https://www.nytimes.com/games/wordle/index.html)
- [Wordly (unofficial)](https://wordly.org/)

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/wordle-solver.git
   cd wordle-solver





📝 How It Works
This project consists of two key files:

words.txt
This file contains a list of 5757 valid 5-letter English words. These words are used to guide the solver in generating possible guesses based on the feedback you provide after each attempt.

wordle_solver.py
This file contains the Python code that implements the Wordle solving algorithm. It takes your feedback (Green, Yellow, and Gray) after each guess and filters the list of possible words, narrowing down the options until it suggests the correct word in 6 attempts or fewer.


🧩 Example Usage
After running the solver, you will be prompted to enter the feedback for each guess:

👋 Welcome to the Wordle Assistant!
Use 'G' for green, 'Y' for yellow, and 'B' for gray.

✨ Suggested word: CRANE
🧩 Enter feedback (e.g., BYGBB): BGYBB
Next suggestion: STOMP
...

You can continue providing feedback, and the assistant will continue to suggest the next possible words based on the feedback you provide.


🤝 Contributing
Feel free to contribute by submitting issues or pull requests. If you have any suggestions for improving the solver, don’t hesitate to get in touch!
