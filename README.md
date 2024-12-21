# Incorrect usage of $inc operator in MongoDB
This repository demonstrates an example of incorrect usage of the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is provided instead of a number, it will result in an unexpected behavior, the field might be set to the string value instead of incrementing the original value. The correct usage is shown in the solution file.

## Bug
The `bug.js` file shows the incorrect usage of the `$inc` operator where a string is used, which will lead to the counter field being set to the string '1' instead of incrementing.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator. Using a numerical value will correctly increment the counter field. 