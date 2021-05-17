## Read 32

# Custom Hooks

### What does a component’s lifecycle refer to?
Lifecycle Methods

A component’s lifecycle is broadly classified into four parts:

- initialization
- mounting
- updating
- unmounting

### Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect
useCallback will help in avoiding regeneration when rerender

### Why are functional components preferred over class components?
Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks.

### What is wrong with the following code
we cant use the loop for the useEffect 
```
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}
```
## Term

### state hook
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state 
to function components.

### effect hook
The Effect Hook lets you perform side effects in function components: .

### reducer hook
useReducer is used to store and update states, just like the useState Hook.

## Preparation Materials

 [custom hooks ](https://www.telerik.com/kendo-react-ui/react-hooks-guide/#toc-custom-react-hooks)

 [async hooks](https://dev.to/vinodchauhan7/react-hooks-with-async-await-1n9g)

 [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

 [use hooks](https://usehooks.com/)

 [hooks list](https://github.com/rehooks/awesome-react-hooks)

 [10 essential react hooks](https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d)



