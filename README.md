# Incorrect Handling of Negative Numbers in Julia Function

This repository demonstrates a common error in Julia functions: incorrect handling of negative numbers.

The `bug.jl` file contains a function `my_function` that aims to square the input number, handling positive, zero, and negative inputs differently. However, the current implementation does not produce the expected output for negative numbers. The `bugSolution.jl` file presents the corrected version of the function.

## How to reproduce the bug:

1. Clone the repository.
2. Open `bug.jl` in Julia.
3. Run the code. Observe that the output for negative inputs is incorrect.

## Solution

The solution corrects the handling of negative numbers by ensuring the return value is always positive when squaring a number.