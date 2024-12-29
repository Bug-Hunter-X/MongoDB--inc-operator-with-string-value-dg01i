# MongoDB $inc operator with string value
This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator with a string value instead of a numeric value.
The `$inc` operator is used to increment a numeric field by a specified value.  If you use a string, MongoDB will not correctly update the field, likely resulting in unexpected behavior or an error.

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the correct implementation.
