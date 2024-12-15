# React useEffect Infinite Loop Bug
This repository demonstrates a common React bug where an infinite loop occurs within a `useEffect` hook due to improper dependency management. 

The `bug.js` file shows the buggy code where the `useEffect` hook attempts to update the state variable `count` without specifying the `count` variable in dependency array causing an infinite re-render loop.

The `bugSolution.js` file demonstrates how to fix the issue by correctly specifying the dependencies and using the functional update approach for updating states.