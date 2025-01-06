# Expo CLI Error: Unable to resolve module

This repository demonstrates a common error encountered when using the Expo CLI: "Unable to resolve module".  The error occurs when the project attempts to import a module that is either not installed, improperly installed, or located outside the project's accessible paths.

The `bug.js` file shows the problematic code, and the solution in `bugSolution.js` demonstrates how to rectify this error using proper installation and import statements.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` (or `yarn install`) to install the dependencies.
3. Observe the error in `bug.js`.
4. Examine the solution in `bugSolution.js`.

## Solution

The solution typically involves ensuring that the needed modules are correctly installed and their paths are correctly specified in the import statements.