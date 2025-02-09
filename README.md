# Unexpected String Concatenation in JavaScript

This repository demonstrates a common, yet subtle, error in JavaScript:  unexpected string concatenation due to its loose typing system.

The `bug.js` file contains a function that adds two arguments. However, if one argument is a number and the other is a string, the `+` operator performs string concatenation instead of numerical addition, leading to an incorrect result.

The `bugSolution.js` file provides a solution to this issue using type checking to ensure that both inputs are numbers before performing the addition.