## Read 33

# Context API

### Describe use cases for useMemo() and useReducer()
- useReducer takes three positional arguments — a reducer, its initial state, and a function that can return the initial state —
let’s call it init for now. The final argument is optional.
- useMemo will only recompute the memoized value when one of the dependencies has changed. This optimization helps to avoid expensive 
calculations on every render.

### Why do custom hooks need the use prefix?
we have to use it otherwise react wouldn’t be able to automatically check for violations of rules of hooks

### What do custom hooks usually do?
Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value)

### Using any list of custom hooks, research and name one that you think will be useful in your applications
useToggle it the best

### Describe how a hook that fetches API data might work
Fetch provides a generic definition of Request and Response objects (and other things involved with network requests). This will allow them 
to be used wherever they are needed in the future

## Term

### reducer
A reducer is a function that determines changes to an application's state.

## Preparation Materials

### context api
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, 
or preferred language.

### hooks and context example
After performing an audit on how we communicate with our users, we landed with a simple system of three classes of communication, and snackbars fit 
perfectly on the ‘low priority’


