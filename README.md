# Rendering in React

- What causes the re-render?
  - Setter function from useState hook or dispatch function from useReducer hook
  - It doesnt re-render when you update the state to the same value as before
    - same value after initial render: component doesnt re-render
    - same value after re-renders: re-render the component just one more time, susequent function calls wont re-render the component