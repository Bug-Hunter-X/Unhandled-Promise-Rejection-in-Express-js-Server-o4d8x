# Unhandled Promise Rejection in Express.js Server

This repository demonstrates a common error in Express.js applications: unhandled promise rejections.  When an asynchronous operation within a route handler throws an error, the server crashes without providing useful information to the developer.

The `bug.js` file contains the problematic code. The `bugSolution.js` file shows how to properly handle these rejections for a more robust application.

## How to reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `node bug.js`.
4. Observe the server crashing after one second due to the unhandled rejection.
5. Now, run `node bugSolution.js` to see the improved, more robust error handling.