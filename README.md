# MongoDB $inc Operator with String Value
This example demonstrates an uncommon error in MongoDB queries: using a string value with the $inc operator.  The $inc operator is designed to increment a numeric field by a specified amount.  Providing a string will result in an unexpected behavior or a query error.

## Bug
The `bug.js` file demonstrates the incorrect usage of `$inc` with a string value.  This will either fail or produce unexpected results, depending on the MongoDB version.

## Solution
The `bugSolution.js` file shows the corrected approach, using a numerical value with the `$inc` operator for accurate field incrementation.
