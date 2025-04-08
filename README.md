# 🧠 Wordle Solver Assistant

This project is an interactive Python-based assistant that helps you solve the popular game [Wordle](https://www.nytimes.com/games/wordle/index.html) (also playable at [wordly.org](https://wordly.org/)).

It analyzes your feedback from each guess and intelligently suggests the next word to try — guiding you to find the solution in 6 attempts or fewer.

---

## 🎮 What is Wordle?

Wordle is a word puzzle game where you have 6 attempts to guess a secret 5-letter English word.

After each guess, you're given feedback for each letter:
- 🟩 **Green (G)** – the letter is correct and in the correct position
- 🟨 **Yellow (Y)** – the letter is in the word but in the wrong position
- ⬜ **Gray (B)** – the letter is not in the word at all

Your goal is to use that feedback to progressively narrow down the possibilities and guess the correct word.

You can play Wordle here:
- [New York Times version](https://www.nytimes.com/games/wordle/index.html)
- [Wordly (unofficial)](https://wordly.org/)

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/wordle-solver.git
   cd wordle-solver


## example 
👋 Welcome to the Wordle Assistant!
Use 'G' for green, 'Y' for yellow, and 'B' for gray.

✨ Suggested word: CRANE
🧩 Enter feedback (e.g. BYGBB): BGYBB
Next suggestion: STOMP
...

