# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: creating an infinite loop by incorrectly updating state within the effect.  The `bug.js` file contains the problematic code. The solution, in `bugSolution.js`, shows how to resolve the issue using a conditional check outside the state update.