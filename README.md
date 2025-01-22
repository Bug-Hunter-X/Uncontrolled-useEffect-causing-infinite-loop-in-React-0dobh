# Uncontrolled useEffect causing infinite loop in React

This repository demonstrates a common error in React applications involving the `useEffect` hook.  The example showcases an infinite render loop caused by missing dependencies in the `useEffect` call. 

The `bug.js` file contains the erroneous code which exhibits the infinite loop. The `bugSolution.js` file presents a corrected version with the proper dependencies added to the `useEffect` array.

This issue highlights the importance of correctly specifying dependencies in the `useEffect` hook to prevent unexpected behavior and performance issues.