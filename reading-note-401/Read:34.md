## Read 34

# Login and Auth

### Why is the Context API useful?
The React Context API is a way for a React app to effectively produce global variables that can be passed around.

### Can a component outside of a provider get its context?
With the introduction of react-hooks in v16.8.0, you can use context in functional components by making use of useContext hook

### What are some common use cases for using the Context API?
React components are structured like a tree. There is one root node where all the components are connected. In this tree structure, 
the data flows in only one direction — from top to bottom.

### Describe “Context Hell”
Like the callback hell, usual when jQuery was used for everything, the React Context hell is the nasty code you get taking advantage of the React Context API.

## Term

### global state
a global state is a set of local states which are all concurrent with each other. By concurrent, we mean that no two states have 
a cause and effect relationship with each other.

### global context
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, 
theme, or preferred language. 

### provider
 Provider component makes the Redux store available to any nested components that need to access the Redux store.

### consumer
A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

## Preparation Materials

### what is role based access control?
Is a network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in 
RBAC refer to the levels of access that employees have to the network.

### react-cookies component
To be able to access user cookies while doing server-rendering, you can use plugToRequest or setRawCookie.

### react-cookie library
- React hooks are available starting from React 16.8
- Javascript object with all your cookies. The key is the cookie name.


