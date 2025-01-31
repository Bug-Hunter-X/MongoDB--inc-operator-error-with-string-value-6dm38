# MongoDB $inc Operator Error
This example demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment or decrement a numerical field, but attempting to use it with a string value will throw an error.

## Bug
The provided `bug.js` file shows an incorrect usage of `$inc`, attempting to increment a field with a string value.

## Solution
The `bugSolution.js` file demonstrates the correct way to use `$inc`, incrementing a numerical field.
