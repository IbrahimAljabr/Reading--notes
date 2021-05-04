## Read 28

# Component Composition

### Can a parent component access the state of a child component?
In React we can access the child's state using Refs. we will assign a Refs for the child component in the parent component. 
then using Refs we can access the child's state. Creating Refs Refs are created using React.

### What can be passed along in a prop variable?
We can pass data and functions

### How can a child component “know” the state of another component?
The most common method is to make a callback function that the child component will trigger and toss the state values upward.

## Term

### component props
they function similarly to HTML attributes.

### component state
The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the 
behavior of the component.

### application state
It stores a component's dynamic data and determines the component's behavior.

## Preparation Materials

### props.children
you can use props.children on components that represent ‘generic boxes’ and that ‘don’t know their children ahead of time’.





