# COS202 Assignment Documentation

## 1. Mathematical Calculator (MC)
A simple interactive Python calculator supporting:
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Power (^)
- Modulus (%)
- Clear screen (C)
- Exit (OFF)

The program runs in a loop, displaying a menu and prompting the user for an
operator and two numbers. It handles invalid input and division/modulus by
zero gracefully.

### Sample Run
+ 5 3 → Result: 8.0
- 10 4 → Result: 6.0
/ 20 0 → Error: Division by zero is not allowed

## 2. Personal Pocket CGPA Calculator (PPC)
A Python program that computes CGPA using selection control statements
(if/elif) on a 5-point grading scale:
- 70-100 = A (5)
- 60-69 = B (4)
- 50-59 = C (3)
- 45-49 = D (2)
- 40-44 = E (1)
- 0-39 = F (0)

The user enters each course's score and credit unit; the program converts
scores to grade points, then calculates:

CGPA = Total Weighted Points / Total Credit Units

### Sample Run
COS201: Score=75, Grade=A, Credit Unit=3, Weighted Point=15
MTH101: Score=55, Grade=C, Credit Unit=2, Weighted Point=6
PHY101: Score=42, Grade=E, Credit Unit=3, Weighted Point=3

Total CGPA: 3.00 (Second Class Lower)

## Screenshots
See attached images in this folder for sample program outputs.



