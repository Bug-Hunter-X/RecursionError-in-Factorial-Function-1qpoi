# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a proper base case for negative inputs. The factorial function is not defined for negative numbers, leading to infinite recursion and a `RecursionError`.

The `bug.py` file contains the erroneous code.  The `bugSolution.py` file shows how to correct this issue by adding a check for negative inputs.