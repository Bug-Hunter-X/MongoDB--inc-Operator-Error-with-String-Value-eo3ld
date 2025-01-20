# MongoDB $inc Operator Error with String Value

This repository demonstrates an error that occurs when using the `$inc` operator in a MongoDB update query with a string value instead of a numeric value.

The `bug.js` file contains the erroneous code, while `bugSolution.js` shows the corrected implementation.

## Error Description
The `$inc` operator is designed to increment numeric values.  Attempting to use it with a string value results in an error.  This error is often subtle and hard to debug because it doesn't immediately throw a clear JavaScript error; the update simply fails silently.