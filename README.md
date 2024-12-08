# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  lack of error handling when parsing user IDs. The provided `bug.js` file shows a route that attempts to find a user by ID but fails to handle cases where the ID is not a number. This can lead to crashes or unexpected behavior.

The `bugSolution.js` file provides a corrected version with robust error handling, ensuring the application behaves gracefully even with invalid input.