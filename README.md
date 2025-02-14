# Uncommon HTML Bug: Misspelled getElementById

This repository demonstrates a common error in JavaScript when interacting with HTML elements. The error is caused by a misspelling of the standard method `getElementById`, used for accessing elements via their id.

## Bug Description
The bug is the misspelling of `getElementById` as `getElementByIdx`.  This results in a runtime error, as the browser attempts to call a non-existent function.

## Bug Reproduction
1. Open `bug.html` in your browser. 
2. Observe the error in the browser's developer console.

## Bug Solution
The solution is in `bugSolution.html`. This fixes the problem by using the correct function name `getElementById`.