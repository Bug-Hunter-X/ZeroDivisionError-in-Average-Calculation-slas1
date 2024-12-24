# Python Average Calculation Bug
This repository demonstrates a common bug in Python code that calculates the average of a list of numbers: a `ZeroDivisionError` when the list is empty. The bug and its solution are provided with clear explanations.

## Bug
The original code doesn't handle the scenario where an empty list is passed to the average calculation function. This leads to a division by zero, causing the `ZeroDivisionError`.

## Solution
The solution adds a simple check to see if the list is empty. If it is, the function returns 0, preventing the error.  This is a robust way to handle potential errors and make the code more reliable.

## How to Run
1. Clone the repository.
2. Navigate to the project directory.
3. Run the Python files using a Python interpreter.