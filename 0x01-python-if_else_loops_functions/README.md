# 0x01. Python - if/else, loops, functions

This project contains solutions to tasks related to Python programming concepts such as if/else statements, loops, and functions.

## Learning Objectives

By completing this project, you will be able to:

- Explain the reasons why Python programming is awesome
- Understand the importance of indentation in Python
- Use if/else statements to control program flow
- Add comments to your code to enhance readability
- Assign values to variables and perform operations on them
- Utilize while and for loops in your code
- Differentiate between Python's for loop and C's for loop
- Use break and continue statements to modify loop behavior
- Apply else clauses to loops for additional functionality
- Understand the purpose and usage of the pass statement
- Utilize the range function in your programs
- Define and use functions to modularize your code
- Understand the concept of scope in Python
- Interpret traceback messages to identify errors in your code
- Use arithmetic operators for mathematical operations

## Requirements

- Python Scripts:
  - Allowed editors: vi, vim, emacs
  - Interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5
  - Code should follow the Pycodestyle style guide (version 2.8.*)
  - Files should end with a new line
  - The first line of all files should be `#!/usr/bin/python3`
  - All files must be executable
  - A README.md file is mandatory and should be placed at the root of the project folder

- C Scripts:
  - Allowed editors: vi, vim, emacs
  - Compiled on Ubuntu 20.04 LTS using gcc with options -Wall -Werror -Wextra -pedantic -std=gnu89
  - Code should follow the Betty style guide
  - Files should end with a new line
  - You are not allowed to use global variables
  - Each file should contain no more than 5 functions
  - Prototypes of all functions should be included in the corresponding header file (lists.h)
  - Header files should be include guarded

## Project Tasks

### 0. Positive anything is better than negative nothing

Write a Python program that assigns a random signed number to the variable `number` each time it is executed. The program should print whether the number stored in `number` is positive, negative, or zero.

- The variable `number` will store a different value every time the program is run.
- The output should be formatted as follows:
  - If the number is greater than 0: "The number is positive"
  - If the number is 0: "The number is zero"
  - If the number is less than 0: "The number is negative"

### 1. The last digit

Write a Python program that assigns a random signed number to the variable `number` each time it is executed. The program should print the last digit of the number stored in `number` along with additional information.

- The variable `number` will store a different value every time the program is run.
- The output should be formatted as follows:
  - "Last digit of `number` is `last_digit` and is greater than 5" if the last digit is greater than 5.
  - "Last digit of `number` is `last_digit` and is 0" if the last digit is 0.
  - "Last digit of `number` is `last_digit` and is less than 6 and not 0" if the last digit is less than 6 and not.

