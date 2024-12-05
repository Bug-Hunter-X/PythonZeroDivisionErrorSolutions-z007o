# ZeroDivisionError Bug in Python

This repository demonstrates a common Python error: `ZeroDivisionError`. The `bug.py` file contains code that attempts to divide by zero, resulting in an error. The `bugSolution.py` file provides a solution using exception handling to gracefully manage this scenario.

## How to Reproduce

1. Clone this repository.
2. Run `bug.py` using a Python interpreter. You'll see a `ZeroDivisionError`.
3. Run `bugSolution.py` to see how to handle this error properly.

## Solution

The solution involves using a `try-except` block to catch the `ZeroDivisionError` and provide a more appropriate response instead of program termination.