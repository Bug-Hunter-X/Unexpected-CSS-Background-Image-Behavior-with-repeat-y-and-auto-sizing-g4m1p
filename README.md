# Unexpected CSS Background Image Behavior

This repository demonstrates a subtle bug in CSS related to background images, specifically when using `background-repeat: repeat-y` in conjunction with `background-size: auto 100%`.  The expected behavior is a vertically repeating background image that scales its width to fit the container. However, the image does not appear.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` file offers a solution.

## Solution

The solution involves understanding and correcting the interaction between `background-repeat` and `background-size`.  The provided solution demonstrates how to achieve the desired effect correctly.