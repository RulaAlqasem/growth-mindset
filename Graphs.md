## 401 Reading Notes: Class 35

### Reading: Implementation: Graphs

A graph is a non-linear data structure that can be looked at as a collection of `vertices` (or `nodes`) potentially connected by line segments named `edges`.

### Terms

- Vertex: A vertex, also called a `node`, is a data object that can have zero or more adjacent `vertices`.
- Edge: An edge is a connection between two `nodes`.
- Neighbor: The `neighbors` of a `node` are its adjacent `nodes`, i.e., are connected via an `edge`.
- Degree: The `degree` of a `vertex` is the number of `edges` connected to that `vertex`.
- Cycle: A cycle is when a node can be traversed through and potentially end up back at itself 
- defined as a path of a positive length that starts and ends at the same vertex
- Weighted Graph: is a graph with numbers assigned to its edges. These numbers are called weights. This is what a weighted graph looks like:

### Directed vs Undirected

An `Undirected Graph` is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.

A `Directed Graph` also called a Digraph is a graph where every edge is directed.

### Complete vs Connected vs Disconnected

A complete graph is when all nodes are connected to all other nodes.

A connected graph is graph that has all of vertices/nodes have at least one edge.

A disconnected graph is a graph where some vertices may not have edges.

### Acyclic vs Cyclic

An acyclic graph is a directed graph without cycles.

A Cyclic graph is a graph that has cycles.

### Graph Representation

- An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix

- An Adjacency list is a collection of linked lists or array that lists all of the other vertices that are connected.

### Traversals

Breadth First
1. `Enqueue` the declared start node into the Queue.
2. Create a loop that will run while the node still has nodes present.
3. `Dequeue` the first node from the queue
4. if the `Dequeue'd` node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.

Depth First

1. `Push` the root node into the stack
2. Start a while loop while the stack is not empty
3. `Peek` at the top node in the stack
4. If the top node has unvisited children, mark the top node as visited, and then `Push` any unvisited children back into the stack.
5. If the top node does not have any unvisited children, Pop that node off the stack
6. repeat until the stack is empty.

### Uses Case for Graphs

- GPS and Mapping
- Driving Directions
- Social Networks
- Airline Traffic
- Netflix uses graphs for suggestions of products
- Neural networks
- Search engine crawlers
- Garbage collection
