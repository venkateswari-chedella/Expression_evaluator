Expression Evaluator
Problem Statement
Mathematical expressions can become difficult to evaluate manually when they contain multiple operators, parentheses, functions, variables, and different levels of operator precedence. Using built-in evaluation functions such as eval() can also be unsafe and provides little understanding of how expression processing works.
This project solves the problem by developing a custom Expression Evaluator in Python that tokenizes, parses, and evaluates mathematical expressions without using Python's built-in eval() function.
Project Overview
The Expression Evaluator is an interactive command-line application that accepts mathematical expressions from the user and calculates their results.
It uses tokenization, stacks, operator precedence, expression parsing, and function handling to process expressions.
The evaluator can also store variables, create user-defined functions, calculate percentages, maintain calculation history, and provide meaningful error messages.
Features
Basic arithmetic operations
Addition +
Subtraction -
Multiplication *
Division /
Modulus %
Power ^
Operator precedence
Parentheses and nested expressions
Decimal numbers
Negative numbers
Mathematical functions
sqrt()
sin()
cos()
tan()
log()
ln()
abs()
floor()
ceil()
factorial()
Mathematical constants
pi
e
Variables
User-defined functions
Percentage calculations
Calculation history
Variable listing
Function listing
Division-by-zero detection
Invalid expression detection
Interactive command-line interface
