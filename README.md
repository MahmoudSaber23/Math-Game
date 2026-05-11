# Math Quiz Game

A console-based math quiz game written in C++.  
The game generates random arithmetic questions based on user-selected difficulty and operation type, helping players practice basic math skills while reinforcing core C++ programming concepts.

---

## Features

- Choose number of questions (1 to 100).
- Select difficulty level:
  - Easy: Numbers from 1 to 10  
  - Medium: Numbers from 20 to 50  
  - Hard: Numbers from 50 to 100  
  - Mix: Random difficulty per question  

- Select operation type:
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  
  - Modulus  
  - Mix (random operation per question)

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

- Recommended IDEs:
  - Visual Studio
  - Code::Blocks
  - Any C++ compiler that supports C++11 or higher
