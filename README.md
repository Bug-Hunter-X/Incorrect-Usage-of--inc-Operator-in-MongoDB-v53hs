# Incorrect Usage of $inc Operator in MongoDB
This repository demonstrates an uncommon error in MongoDB: incorrect usage of the `$inc` operator. The `$inc` operator is used to increment a numerical field in a document.  However, if a string is passed to the `$inc` operator, MongoDB will throw an error.
The `bug.js` file shows the problematic code. The `bugSolution.js` provides the corrected version.