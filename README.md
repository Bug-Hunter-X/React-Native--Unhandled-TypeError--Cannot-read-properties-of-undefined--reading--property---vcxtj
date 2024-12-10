# React Native: Handling Unhandled TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications and provides a solution.  The error, 'Unhandled TypeError: Cannot read properties of undefined (reading 'property')', typically arises when attempting to access a property of an object before the object or its property has been properly defined or populated. This often happens when dealing with asynchronous operations or when component state is not initialized correctly.

## Bug Description
The core issue is accessing a property of a potentially null or undefined object.  This can cause the app to crash unexpectedly.

## Solution
The solution involves using optional chaining (?.) or the nullish coalescing operator (??) to safely access object properties.  This approach gracefully handles cases where the object or property might be undefined, preventing the error.

## Usage
1. Clone the repository
2. Run `npm install`
3. Run the app using your preferred React Native method
4. Observe the bug in the original `bug.js` and the fix in `bugSolution.js`

This example utilizes optional chaining, but you can adapt the same principles for using the nullish coalescing operator as well.