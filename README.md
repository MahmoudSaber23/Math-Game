# Math Quiz Game

A console-based math game written in C++ that challenges the player with randomly generated arithmetic questions based on selected difficulty levels and operation types.

This project is a simple but complete application for practicing core C++ concepts such as functions, enums, structs, randomization, and game loops.

---

## Features

- Choose how many questions you want to answer (from 1 to 100).
- Select a difficulty level:
  - Easy: Numbers from 1 to 10
  - Medium: Numbers from 10 to 50
  - Hard: Numbers from 50 to 100
  - Mix: Random difficulty for each question

- Choose an operation type:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Mix (random operation for each question)

- Automatically checks answers and provides immediate feedback.
- Tracks correct and wrong answers during the quiz.
- Displays final results as Pass or Fail.
- Allows the player to replay the game after finishing a quiz.

---

## How It Works

1. The program asks the player to choose:
   - The number of questions.
   - The difficulty level.
   - The type of arithmetic operation.

2. Based on the selected options, the program generates random math questions.

3. For each question:
   - The player enters an answer.
   - The program checks whether the answer is correct.
   - The score is updated in real time.

4. At the end of the quiz:
   - The final result is displayed.
   - The player can choose to play again or exit.

---

## Input Validation

- The program validates user input to ensure only numeric values are accepted.
- Invalid input does not crash the program.
- The user is repeatedly prompted until valid input is entered.

---

## Technologies Used

- Language: C++
- Libraries:
  - <iostream>
  - <cstdlib>
  - <ctime>

- Recommended IDEs:
  - Visual Studio
  - Code::Blocks
  - Any C++ compiler that supports C++11 or higher
