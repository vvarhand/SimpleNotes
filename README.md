# Simple Notes app created with React.js

Worked with Figma, React (useState & useEffect), conditional rendering...
Got more practice with CSS (MB. - it does get better with time).

## Working with side effects in React

React cannot handle side effects on its own :
    * localStorage
    * API/db calls
    * Web sockets
    * 2+ internal states

notes about `useEffect()`:
1. callback fn() -> runs after render of state
2. dependencies array  -> if vals in array change, effect will run