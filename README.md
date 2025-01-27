# CSS Specificity Bug: Rule Order and Equal Specificity

This repository demonstrates a common CSS specificity issue related to rule order and equal specificity.  The bug arises when two CSS rules have the same specificity, and the order of the rules affects which rule is applied.

## Bug Description
The issue lies in the unexpected behavior of CSS rule application when rules have equal specificity. The later rule is not always applied, leading to inconsistent styling across browsers.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.  You will observe unexpected coloring of the paragraph element.

## Solution
The solution involves understanding and managing CSS specificity. The solution file, `bugSolution.css`, demonstrates proper techniques to resolve this inconsistency.

## Technologies Used
* CSS