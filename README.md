# JavaScript Bug: TypeError when accessing 'length' of undefined

This repository demonstrates a common JavaScript error: a `TypeError` thrown when trying to access the `length` property of an undefined variable.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version that handles the undefined case.

The error occurs when the `foo` function receives an undefined value as input. The solution adds a check to see if the input is undefined before attempting to access the `length` property.  This prevents the error from occurring and ensures the function behaves as intended even with unexpected input.