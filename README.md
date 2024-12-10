# Unexpected NaN Result from Adding Undefined to Number

This repository demonstrates a common, yet often overlooked, JavaScript bug: adding `undefined` to a number results in `NaN` (Not a Number). This can lead to unexpected behavior and difficult-to-track errors in applications.

## The Bug
The `bug.js` file contains a simple function that adds two numbers. However, if the second argument is `undefined`, the result is `NaN`, rather than throwing an error or producing a more predictable outcome.

## The Solution
The `bugSolution.js` file demonstrates how to address this issue using a simple check to handle `undefined` values before performing the addition. This makes the code more robust and easier to understand. 

## How to reproduce
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred code editor or IDE.
3. Run both files in a JavaScript environment (e.g., Node.js, browser's console). Note the difference in output. 
