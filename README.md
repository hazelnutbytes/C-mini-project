# Productivity Timer – C++ Mini Project

## Project Description

The Productivity Timer is a terminal-based application built using C++ and Object-Oriented Programming principles.  
It allows users to manage focused work sessions through structured timer modes such as Sprint, Break, Custom Timer, and Pomodoro cycles.

This project demonstrates practical implementation of core OOP concepts in a real-world productivity utility.

---

## Features

1. Sprint Mode (40-minute focus session)
2. Break Mode (5-minute rest session)
3. Custom Timer (user-defined minutes with optional seconds)
4. Pomodoro Mode (25-minute work + 5-minute break cycles)
5. Real-time countdown display
6. Dynamic progress indicators for minutes and seconds
7. Sound alert when the timer completes
8. Menu-driven interface

---

## OOP Concepts Implemented

- Classes and Objects
- Inheritance
- Function Overloading
- Encapsulation
- Loops and Conditional Statements

---

## Class Structure

Parent Class: Timer  
- Handles countdown logic  
- Formats and displays remaining time  
- Displays progress indicators  
- Plays alert sound on completion  

Child Class: TimerModes  
- Displays main menu  
- Implements different timer modes  
- Calls inherited timer functions  

---

## Project Structure

Productivity-Timer/
│
├── countdown.cpp
├── alert.wav
├── Documentation.docx
├── Presentation.pptx
└── README.md

Note: Build files such as compiled executables, .vscode/, and countdown.dSYM/ are excluded using .gitignore.

---

## Compilation and Execution

Step 1: Compile
g++ countdown.cpp -o countdown

Step 2: Run
./countdown

Note:  
The project uses the "afplay" command to play the alert sound, which works on macOS.  
For Windows systems, the sound command must be modified accordingly.

---

## Conclusion

The Productivity Timer successfully demonstrates the use of Object-Oriented Programming in C++ through a structured and interactive terminal application.  
It combines inheritance, function overloading, and dynamic output formatting to create a practical time-management tool.
