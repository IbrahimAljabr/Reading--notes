## Read 37

# Combined Reducers

### Why choose Redux instead of the Context API for global state?
It's more stable for big projects

### What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change.

### What does an action contain?
 contain information or data.
 
### Why do we need to copy the state in a reducer?
Edit: about making a copy

## Term

### immutable state
Immutable state is state that cannot be changed.

### time travel in redux
When inspect the state and travel back in time to a previous application state without reloading the page or restarting the app.

### action creator
An action creator is merely a function that returns an action object. ... Calling an action creator does nothing but return an object, 
so you have to either bind it to the store beforehand, or dispatch the result of calling your action creator.

### reducer
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change.

### dispatch
dispatch is a function of the Redux store. You call store. dispatch to dispatch an action.

## Preparation Materials

### Redux Docs: Using Combined Reducers
Redux provides the combineReducers utility to implement that behavior. It is an example of a higher-order reducer, which takes 
an object full of slice reducer functions, and returns a new reducer function.

