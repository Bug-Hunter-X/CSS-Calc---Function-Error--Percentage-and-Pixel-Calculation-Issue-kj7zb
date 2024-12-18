# CSS Calc() Function Error: Percentage and Pixel Calculation Issue

This repository demonstrates a common, yet subtle, error that can occur when using the `calc()` function in CSS to calculate widths or other properties involving percentages and pixels.  The issue arises from an unexpected interaction between the percentage and pixel values within the `calc()` expression.

The `bug.css` file contains the erroneous code. The `bugSolution.css` file provides a corrected version.

## How to reproduce the bug:

1.  Create a simple HTML file that includes a `div` element.
2.  Link the `bug.css` file to your HTML file.
3.  Observe the unexpected rendering of the `div`. 

## Solution:

The solution involves ensuring consistent handling of units within the calculation.  Details are explained in the comments within `bugSolution.css`. 