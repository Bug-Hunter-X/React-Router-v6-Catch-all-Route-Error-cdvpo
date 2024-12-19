# React Router v6 Catch-all Route Error

This repository demonstrates a common error encountered when using catch-all routes (`/*`) in React Router v6.  The issue arises when a catch-all route is placed after more specific routes.  This results in an error because the catch-all route unintentionally matches all paths, including those already handled by the preceding routes.

The `App.js` file contains the erroneous code, while `AppSolution.js` provides the corrected implementation.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe the error in your browser's console.

## Solution

The solution involves reordering routes, placing catch-all routes at the very end of the route definitions. See `AppSolution.js` for the corrected implementation.