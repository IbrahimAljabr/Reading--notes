## Read 39

# Redux - Additional Topics

### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
Answer. The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle 
method (probably componentWillMount ) of a Higher Order Component that wraps your app.

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
You can manage asynchronous actions in Redux with Thunk, or you could ... that you dispatch the action that starts the asynchronous task. 

## Term

### middleware
What is Middleware? ... Middleware allows for side effects to be run without blocking state updates. We can run side effects (like API requests) 

### thunk
Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. 

## Preparation Materials

### Redux Toolkit (RTK)
The Redux Toolkit package is intended to be the standard way to write Redux logic.

### MobX
MobX is a simple, scalable and battle tested state management solution. 

### HookState
Hookstate is a modern alternative to Redux, Mobx, Formik without boilerplate.




