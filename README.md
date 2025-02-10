# React setInterval Memory Leak

This repository demonstrates a common error in React applications involving the use of `setInterval` within the `useEffect` hook.  Failure to properly clean up the interval leads to a memory leak when the component unmounts.

The `bug.js` file shows the erroneous code.  The `bugSolution.js` file provides the corrected code with proper cleanup.