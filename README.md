# CSS calc() Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to operator precedence and unit mismatches.

## Bug Description
The `calc()` function, while powerful, can be tricky.  Incorrect unit usage or unexpected operator precedence can lead to layout problems and unexpected rendering.

## Bug Reproduction
See `bug.css` for the problematic code.

## Solution
The `bugSolution.css` file provides corrected code with clear unit handling and parenthesis for improved order of operations, fixing the calculation errors.