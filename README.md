# Subtle CSS `calc()` Error: Missing Space Between Operator and Value

This repository demonstrates a common, yet easily missed, error when using the `calc()` function in CSS.  The issue arises from a missing space between the arithmetic operator and the value in the calculation. This can lead to unexpected layout results, especially in more complex calculations.

## Bug

The `bug.css` file contains the incorrect CSS code. Observe that there's no space between the `-` operator and the `10px` value in the `height` property calculation.

## Solution

The `bugSolution.css` file shows the corrected CSS, with the necessary spaces added to ensure proper interpretation by the browser.

## Reproduction

1. Open `bug.html` in your browser.
2. Observe the unexpected rendering of the element.
3. Replace `bug.css` with `bugSolution.css`.
4. Observe the corrected rendering. 
