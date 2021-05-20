## Read 35

# Graphs
A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

### Undirected Graphs
An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

### Directed Graphs (Digraph)
A Directed Graph also called a Digraph is a graph where every edge is directed.

### Complete Graphs
A complete graph is when all nodes are connected to all other nodes.

### Connected
A connected graph is graph that has all of vertices/nodes have at least one edge.

### Disconnected
A disconnected graph is a graph where some vertices may not have edges.

### Acyclic Graph

- An acyclic graph is a directed graph without cycles.

- A cycle is when a node can be traversed through and potentially end up back at itself.

### Cyclic Graphs

- A Cyclic graph is a graph that has cycles.

- A cycle is defined as a path of a positive length that starts and ends at the same vertex.

## Graph Representation

### Adjacency Matrix

An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix

### Adjacency List

- An adjacency list is the most common way to represent graphs.

- An adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

- Adjacency lists make it easy to view if one vertices connects to another.

### Weighted Graphs
A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights.

## Traversals

### Breadth First
In a breadth first traversal, you are starting at a specific vertex/node. This node must be specified when calling the BreadthFirst() method. 
The breadth-first traversal of a graph is like that of a tree

### Depth First

In a depth first traversal, we approach it a bit different than the way we do when working with a depth first traversal of a tree. Similar to how the 
breadth-first uses a queue, we are going to use a Stack for our depth-first traversal.


