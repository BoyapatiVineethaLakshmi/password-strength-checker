**Password Strength Checker**: 

A comprehensive password strength checking tool with both GUI and CLI interfaces. This application helps users create and validate secure passwords using advanced strength checking algorithms.

Features
1. Dual Interface: Choose between a user-friendly GUI or efficient CLI
2. Password Strength Analysis: Uses the zxcvbn algorithm for realistic password strength assessment
3. Password Generation: Create strong, random passwords of customisable length
4. Comprehensive Checks:
   a. Minimum length requirements
   b. Character complexity (uppercase, lowercase, numbers, special characters)
   c. Common password detection
   d. Banned password detection
5. Improvement Suggestions: Get specific recommendations to strengthen weak passwords
6. Export Functionality: Save password check results to JSON (GUI mode)

**Running in ComandLine:**

python password_strength_checker.py

Interactive CLI:

python password_strength_checker.py --cli

Direct password check:

python password_strength_checker.py --check "your_password_here"

Generate password:


**Dependencies:**

Python 3.x

tkinter (included in standard Python distribution)

zxcvbn
