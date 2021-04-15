## Read 14

# Trees

### Common Terminology

- Node - A Tree node is a component which may contain it’s own values, and references to other nodes.
- Root - The root is the node at the beginning of the tree.
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree.
- Right - A reference to the other child node, in a binary tree.
- Edge - The edge in a tree is the link between a parent and child node.
- Leaf - A leaf is a node that does not have any children.
- Height - The height of a tree is the number of edges from the root to the furthest leaf.

### Traversals
An important aspect of trees is how to traverse them. Traversing a tree allows us to search for a node.and much more! There are two categories 
of traversals when it comes to trees:

- Depth First
- Breadth First

### Depth First
Depth first traversal is where we prioritize going through the depth (height) of the tree first. 

- Pre-order: root >> left >> right
- In-order: left >> root >> right
- Post-order: left >> right >> root

### Breadth First
Breadth first traversal iterates through the tree by going through each level of the tree node-by-node. So, given our starting tree one more time

### Binary Tree Vs K-ary Trees
Trees can have any number of children per node, but Binary Trees restrict the number of children to two (hence our left and right children).

### K-ary Trees
f Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the 
maximum number of children that each Node is able to have.

### Breadth First Traversal
Traversing a K-ary tree requires a similar approach to the breadth first traversal. We are still pushing nodes into a queue, but we are now 
moving down a list of children of length k, instead of checking for the presence of a left and a right child.

### Adding a node
One strategy for adding a new node to a binary tree is to fill all “child” spots from the top down.

### Big O
The Big O time complexity for inserting a new node is O(n). Searching for a specific node will also be O(n)
The Big O space complexity for a node insertion using breadth first insertion will be O(w), where w is the largest width of 
the tree. For example, in the above tree, w is 4.

### Binary Search Trees
A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST

### Searching a BST
Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the 
tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.

### Big O
the height of the tree is log(n). In an unbalanced tree, the worst case height of the tree is n.
The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.





