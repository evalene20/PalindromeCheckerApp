# PalindromeChecker App  
**App-Based Learning Using Core Java & Data Structures**

## Overview
The PalindromeChecker App is a console-based Java application designed to validate whether a given string is a palindrome under different conditions.

This project focuses on strengthening core programming fundamentals while demonstrating how basic data structures and algorithms are applied to solve real-world string processing problems.

---

## Objective
The objective of this project is to design and implement a system that:

- Checks whether a string is a palindrome
- Handles multiple validation conditions (case sensitivity, ignoring spaces/special characters)
- Reinforces problem-solving using data structures
- Builds a strong foundation in Core Java programming

---

## Key Features

### 1. Basic Palindrome Validation
- Checks if a string reads the same forward and backward  
- Example: "madam", "level"

### 2. Case-Insensitive Checking
- Treats uppercase and lowercase letters as equal  
- Example: "Madam" → valid palindrome  

### 3. Ignoring Special Characters
- Removes spaces and non-alphanumeric characters before validation  
- Example: "A man, a plan, a canal: Panama"  

### 4. Multiple Approaches
- String reversal method  
- Two-pointer technique  
- Stack-based approach (optional enhancement)  

---

## Learning Approach

This project follows a step-by-step enhancement model:

- Start with simple string comparison
- Introduce input normalization techniques
- Apply data structures like stacks
- Optimize using efficient algorithms (two-pointer method)

### Focus Areas
- Core Java (Strings, Methods, Control Flow)
- Data Structures (Stack, Arrays)
- Algorithm Design (Two-pointer technique)
- Clean and Readable Code Practices

---

## Project Structure
<img width="430" height="238" alt="image" src="https://github.com/user-attachments/assets/fb6406fd-ea4d-4678-853a-354e7bdf68ed" />


---

## Technologies Used

- Java (Core Java)
- Java Collections Framework (Stack)
- Object-Oriented Programming Principles

---

## How It Works

1. User provides a string input
2. System preprocesses the string (optional normalization)
3. Different algorithms are applied to check palindrome
4. Result is displayed as true or false

---

## Scope & Limitations

- Console-based application (no graphical UI)
- No persistent storage
- Handles single input at a time

---

## Future Enhancements

- Add GUI (Swing / JavaFX)
- Accept multiple inputs in batch mode
- Add performance comparison between algorithms
- Extend to phrase and sentence-level analysis
- Build REST API version

---

## Learning Outcome

By completing this project, you will:

- Understand string manipulation in Java
- Learn multiple approaches to solve the same problem
- Gain experience with stacks and algorithm optimization
- Improve logical thinking and coding efficiency

---

## Getting Started

### Prerequisites
- Java JDK 8 or above
- Any IDE (IntelliJ IDEA, Eclipse, VS Code)

### Run the Project

```bash
# Compile
javac Main.java

# Run
java Main
