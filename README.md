# React Router Dom v6 Nested Route with Params Issue

This repository demonstrates a bug in React Router Dom v6 when using nested routes with parameters. The nested route fails to render correctly, resulting in a blank screen. The issue occurs only when there is a route with parameters in a nested route path. 

## Steps to reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm start`.
4. Navigate to `/users/1`.

Expected behavior:
The User component should be rendered with id 1

Actual behavior:
Blank screen

## Solution
The solution involves restructuring the routes by removing the unnecessary nesting or using a different approach to handle the nested route with parameters. The updated `bugSolution.js` demonstrates a working solution.