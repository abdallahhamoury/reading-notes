# Read: Trees

---------------------------------------------------------------------------------
A binary tree is a recursive data structure where each node can have 2 children at most. A common type of binary tree is a binary search tree, in which every node has a value that is greater than or equal to the node values in the left sub-tree, and less than or equal to the node values in the right sub-tree

To implement this algorithm, you can write a method to traverse all nodes of the binary tree using InOrder traversal by following these steps:
Write a method in Order(TreeNode)
Check if node == is empty, and if yes, return, then this is our base case.
call inOrder node.
Print the node value.
Call inOrder node

### Traversals

- Depth First
Depth First Search (DFS) is a traversal algorithm used for both tree and graph data structures. The first research delves deeper into each branch before moving on to explore another.

- Breadth First

First Scope Lookup (BFS) is based on traversal of nodes by adding each node's neighbor starting from the root node to the traversal queue. BFS Graph Similar to Tree


#### Binary Tree Vs K-ary Trees

A binary tree for which the root node does not have a suitable branch can be considered as a public tree, and any binary tree can be considered as a set (forest) of public trees. A K-ary tree is a tree in which no node can have more than K children. A binary tree is an example of a K-ary tree, where K equals 2

#### Binary Search Trees in java
A binary search tree (hereafter BST) is a type of binary tree. It can also be defined as a node-based binary tree. BST is also referred to as "Binary Ordered Tree". In BST, all nodes in the left subtree have values less than the value of the root node
