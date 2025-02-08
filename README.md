# Unhandled Next.js router.push Error

This repository demonstrates a common error encountered when using the `router.push` method in Next.js: navigating to a route that does not exist. The application does not handle this error gracefully.

## The Problem

The `bug.js` file contains a component that uses `router.push` to navigate to a non-existent route. When this happens, Next.js throws an error, and the user experience is disrupted.  The goal is to improve error handling and present a better user experience.

## The Solution

The `bugSolution.js` file shows how to solve this issue by implementing proper error handling.  This improved version checks for the route's existence before attempting navigation, providing a fallback or displaying a user-friendly message if the route is invalid.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the Next.js development server.
4. Click the button in the browser.  The original code will throw an error; the solution will handle it gracefully. 
