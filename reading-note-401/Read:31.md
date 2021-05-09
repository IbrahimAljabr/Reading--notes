## Read 31

# Hooks API

### Why do we not need more .html pages in a multi-page React app?
React is a single page application, it will rerender on every update happen at the same page.

### If we wanted a component to show up on every page, where would we put it and why? 
Inside the <BrowserRouter />, outside a <Route />, we need to put it outside the <Route /> so it stay if you change the routs

### What does props.children contain?
It is used to display whatever you include between the opening and closing tags when invoking a component.

## Term

### Composition
Is a pattern that can be used to break a complex component down to smaller components, and then composing those smaller components to 
structure and complete your application.

### Children / Child Components
Is a special property of React components which contains any child elements defined within the component

### Hash Routing
It uses URL hash, it puts no limitations on supported browsers or web server. Server-side routing is independent from client-side routing.

### Link Routing
Provides declarative, accessible navigation around your application.

## Preparation Materials

### making sense of hooks
We are useing hook for 
- Huge components that are hard to refactor and test.
- Duplicated logic between different components and lifecycle methods.
- Complex patterns like render props and higher-order components.

### the state hook
- What is a Hook? A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add 
React state to function components. We’ll learn other Hooks later.
- When would I use a Hook? If you write a function component and realize you need to add some state to it, previously you had to convert it 
to a class. Now you can use a Hook inside the existing function component.

### hooks api
The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as 
componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API.

### hooks api reference

basic
- useState
- useEffect
- useContext
Additional Hooks
- useReducer
- useCallback
- useMemo
- useRef
- useImperativeHandle
- useLayoutEffect
- useDebugValue

### effects hook
By using this Hook, you tell React that your component needs to do something after render. React will remember the 
function you passed and call it later after performing the DOM updates.
