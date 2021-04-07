## Read Stacks and Queues

### What is a Stack?

A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.

### FILO
First In Last Out

### Push 
Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you 
have in the stack.

### Pop 
Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will be re-assigned to the 
Node that lives below and the top Node is returned to the user.

### Peek 
When conducting a peek, you will only be inspecting the top Node of the stack.

### Enqueue
When you add an item to a queue, you use the enqueue action. This is done with an O(1) operation in time because it does not matter how many 
other items live in the queue (n); it takes the same amount of time to perform the operation.

### Dequeue 
When you remove an item from a queue, you use the dequeue action. This is done with an O(1) operation in time because it doesn’t matter how many other 
items are in the queue, you are always just removing the front Node of the queue.

