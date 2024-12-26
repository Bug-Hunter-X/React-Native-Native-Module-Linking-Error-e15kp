# React Native Native Module Linking Error

This repository demonstrates a common issue in React Native development: errors related to linking native modules.  The problem occurs when a third-party library with native dependencies isn't properly integrated into the project. This leads to runtime errors, typically `undefined is not an object (evaluating 'RNSomeLibrary.someMethod')`, indicating that the JavaScript code can't find the native module functions.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides the solution.