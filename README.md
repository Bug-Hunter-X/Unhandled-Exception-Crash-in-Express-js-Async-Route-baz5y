# Unhandled Exception Crash in Express.js Async Route

This repository demonstrates a common error in Express.js applications: unhandled exceptions within asynchronous route handlers.  The server crashes without proper error handling if an asynchronous operation fails.

## Bug Description
The `bug.js` file contains an Express.js application with a route that simulates an asynchronous operation.  This operation randomly throws an exception, causing the server to crash without any graceful handling.

## Solution
The `bugSolution.js` file demonstrates how to properly handle potential errors using `try...catch` blocks within asynchronous route handlers.  This prevents the server from crashing and allows for more robust error management.