# JavaScript Null Handling Error

This repository demonstrates a common JavaScript error involving improper null handling.  The `bug.js` file contains a function that fails to handle null values correctly. The `bugSolution.js` file provides a corrected version.

## Bug Description

The `foo` function adds two numbers. However, it does not explicitly handle cases where either input is `null` or `undefined`. This can lead to unexpected behavior or errors.

## Solution

The solution involves adding explicit checks for `null` or `undefined` values before performing the addition operation.  Appropriate error handling or default values are used to prevent unexpected behavior.