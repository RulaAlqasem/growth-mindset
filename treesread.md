[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-15

### Implementation: Trees


- Binary Search Tree is a node-based binary tree data structure which has the following properties:

  - The left subtree of a node contains only nodes with keys lesser than the node’s key.
  - The right subtree of a node contains only nodes with keys greater than the node’s key.
  - The left and right subtree each must also be a binary search tree.

 ### terms 

 - A binary tree is made of nodes, where each node contains a "left" pointer, a "right" pointer, and a data element. 
 - The "root" pointer points to the topmost node in the tree. 
 - The nodes at the bottom edge of the tree have empty subtrees and are called "leaf" nodes


 - **Edge**	Link between parent/child node


 ### Depth Vs width Search

 - The depth of a node in a binary tree is the total number of edges from the root node to the target node. Similarly, the depth of a binary tree is the total number of edges from the root node to the most distant leaf node

 - The width of a binary tree is the number of nodes present at the given level. So here we will see how we can find the width at each level and return the maximum width of the tree. We will use two different methods to find the width of BST

 - A balanced binary tree, also referred to as a height-balanced binary tree, is defined as a binary tree in which the height of the left and right subtree of any node differ by not more than 1


### Tree traversal
Another frequently used tree operation is traversal. Tree traversal is the process of visiting each node present in a tree. There are three methods of tree traversal:

- In-order traversal
- Post-order traversal
- Pre-order traversal


![WhiteBoard](./treeim.png)
