# MongoDB $inc operator error
This repository demonstrates an example of an uncommon error related to the use of the `$inc` operator in MongoDB update operations.
The error occurs due to providing a string value to the `$inc` operator instead of a number.  The `$inc` operator expects a numerical value to increment the field by. Providing a string will lead to a failure or unexpected results.
The solution provided demonstrates the correct usage of the `$inc` operator.