# Unexpected behavior of :nth-child CSS selector

This repository demonstrates a bug related to the unexpected behavior of the `:nth-child(n)` CSS selector. The bug occurs when the selector is used in conjunction with dynamic DOM manipulations or complex selector combinations.  The index of elements selected by `:nth-child` can change unexpectedly, leading to unexpected styling inconsistencies. This example shows the issue and provides a solution.

## Bug

The `bug.css` file shows the problematic code.

## Solution

The `bugSolution.css` file contains a solution.  In some cases, more robust techniques involving JavaScript might be necessary to manage styling based on dynamic changes to the DOM.