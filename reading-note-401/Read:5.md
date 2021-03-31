## Read 5

# Linked Lists

### What is a Linked List

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a 
Linked List is that each Node references the next Node in the link.

### Traversal Big O

The Big O of time for Includes would be **O(n)**. This is because, at its worse case, the node we are looking 
for will be the very last node in the linked list. n represents the number of nodes in the linked list.

The Big O of space for Includes would be **O(1)**. This is because there is no additional space being used than 
what is already given to us with the linked list input.

### Memory management

The biggest differentiator between arrays and linked lists is the way that they use memory in our machines. 
Those of us who work with dynamically typed languages like Ruby, JavaScript, or Python don’t have to think about how much 
memory an array uses when we write our code on a day to day basis because there are several layers of abstraction that end up 
with us not having to worry about memory allocation at all.


### To list or not to list?

No human is perfect, and neither is a linked list. Here’s the thing: sometimes, a linked 
list can be really awesome — for example, when you want to insert or remove something at the 
beginning of the list. But, as we’ve learned, they can sometimes be…less than ideal (imagine having a 
million nodes and just wanting to delete the last one!)












