# CSS calc() Gotcha: Operator Precedence and Spacing

This repository demonstrates a common issue encountered when using the CSS `calc()` function: incorrect calculations due to unexpected operator precedence and missing spaces.  The `bug.css` file shows the problematic code, while `bugSolution.css` provides the corrected version.

**Problem:**
The `calc()` function, while powerful, can produce incorrect results if you don't pay attention to operator precedence and spacing.  Parentheses should be used to explicitly define calculation order, and spaces should always be included around operators.

**Solution:**
Always use parentheses (`()`) to clarify the order of operations within the `calc()` function.  Ensure that spaces are present around the `+`, `-`, `*`, and `/` operators. This makes the code more readable and less prone to errors.