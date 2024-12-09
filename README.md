# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: unbounded recursion leading to stack overflow. The `bug.hack` file contains a recursive factorial function that will crash for larger inputs.  The `bugSolution.hack` file provides a corrected, iterative version that avoids this issue.

## How to reproduce

1. Clone this repository.
2. Compile and run `bug.hack`. Observe the stack overflow error for larger inputs (e.g., `foo(100)`).
3. Compile and run `bugSolution.hack`. This version will correctly compute the factorial even for large inputs.

## Lesson Learned

Recursive functions are elegant but need to be carefully designed to prevent infinite recursion.  When dealing with potentially large inputs, iterative solutions often offer superior performance and stability.
