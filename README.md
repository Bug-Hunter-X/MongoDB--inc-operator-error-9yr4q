# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB.  The `$inc` operator is designed to increment a numeric field by a given value.  Attempting to use it with a non-numeric value will result in an error.

## Bug
The `bug.js` file shows the incorrect usage where a string value is passed to the `$inc` operator.  This will lead to a MongoDB error.

## Solution
The `bugSolution.js` file shows the correct usage.  The value passed to `$inc` must be a number. 