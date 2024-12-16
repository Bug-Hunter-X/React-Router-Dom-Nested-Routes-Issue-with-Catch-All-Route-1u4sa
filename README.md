# React Router Dom Nested Routes Issue
This repository demonstrates an unexpected behavior in React Router Dom v6 when using nested routes in conjunction with a catch-all route (`path="*"`).  The catch-all route unexpectedly intercepts routes that should otherwise be handled by nested routes, leading to incorrect navigation and rendering.

## Steps to Reproduce
1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the application: `npm start`
4. Navigate to the application and try to navigate to the nested routes. Observe the unexpected behavior.

## Solution
The solution involves carefully ordering routes and using more specific catch-all routes.