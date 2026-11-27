# Lab-assigment4

# Prompt Quizzer – A Quiz Game

A simple JavaScript quiz game that runs entirely in the browser console. It asks questions using `prompt()`, gives instant feedback using `alert()`, and shows the final score at the end. No HTML or DOM manipulation is needed.

Built as part of **Web Dev I – Lab Assignment 4**.

## Features

- Questions and answers stored in an array of objects (`quizQuestions`)
- Loops through every question using a `for` loop
- Takes user input with `prompt()`
- Normalizes input with `toLowerCase()` and `trim()`, so `" PARIS "` and `"paris"` are both accepted
- Instant feedback with `alert()` (shows the correct answer when wrong)
- Tracks the score and displays it at the end
- Handles the Cancel button without crashing

## Concepts Used

- Arrays and objects
- Functions (`runQuiz()`)
- `for` loops
- Conditional statements (`if`/`else`)
- String methods: `toLowerCase()`, `trim()`
- Template literals
- Browser I/O: `prompt()` and `alert()`

## Project Structure

```
prompt-quizzer/
├── quiz.js
└── README.md
```

## How to Run

1. Open any webpage in Google Chrome (a normal website works best, since some pages block `prompt()`).
2. Press **F12** (or right-click and choose **Inspect**) and open the **Console** tab.
3. Copy the entire code from `quiz.js` and paste it into the console.
   - If Chrome asks, type `allow pasting` and press Enter, then paste again.
4. Press **Enter** to start the quiz.
5. Answer each question in the prompt box and click **OK**.
6. Read the feedback after each question and check your final score at the end.

## Sample Questions

| # | Question | Answer |
|---|----------|--------|
| 1 | What is the capital of France? | Paris |
| 2 | Which planet is known as the Red Planet? | Mars |
| 3 | What is 5 + 7? | 12 |
| 4 | Who is the Prime Minister of India? | Narendra Modi |
| 5 | Which language is used for web development? | JavaScript |

## Sample Flow

1. Prompt: *What is the capital of France?* → type `paris`
2. Alert: *Correct!*
3. Prompt: *Which planet is known as the Red Planet?* → type `venus`
4. Alert: *Wrong! The correct answer is: mars*
5. After the last question: *Quiz Over! Your final score is X out of 5*

## Possible Improvements

- Add more questions
- Add multiple-choice options
- Add a timer for each question
- Show hints for wrong answers
- Save high scores using `localStorage`
- Add a restart option and score-based messages

## Author

**Your Name**
Roll No: YOUR-ROLL-NUMBER
Course: Web Dev I
