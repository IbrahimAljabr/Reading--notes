## Read 38

# Redux - Asynchronous Actions

### How granular should your reducers be?
should separate for each type of data and avoid repeating yourself

### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
con because it might result in performance issues

### Name a strategy for preventing the above
specific names for the represent 

## Term

### Store
 allows components to share state. In a way, we can think of a store as a database. On the most fundamental level, both 
 constructs allow us to store data in some form or another.

### combined reducers
The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . 

## Preparation Materials

### async actions
Just like with a normal action, we first need to handle a user event in the application, such as a click on a button. Then, we call dispatch(), 
and pass in something, whether it be a plain action object, a function, or some other value that a middleware can look for.
Once that dispatched value reaches a middleware, it can make an async call, and then dispatch a real action object when the async call completes.

### redux thunk
The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to 
dispatch actions that follow the lifecycle of a request to an external API.
