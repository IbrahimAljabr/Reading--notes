## Read 10

# THE CALL STACK

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function

- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
- If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

## The JavaScript Call Stack - What It Is and Why It's Necessary

The JavaScript engine is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.

## Types of error messages

- Reference errors
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

- Type errors
this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## Conclusion
Being able to read error messages and practising debugging is one of your biggest weapons has a developer



