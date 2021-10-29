# Trees

A tree data structure can be defined recursively as a collection of nodes, where each node is a data structure consisting of a value and a list of references to nodes. The start of the tree is the "root node" and the reference nodes are the "children". No reference is duplicated and none points to the root.
Wikipedia

# Terminology
Root

The first node from where the tree originates is called as a root node. In any tree, there must be only one root node. We can never have multiple root nodes in a tree data structure.

Node

The node which has at least one child is called as an internal node. Internal nodes are also called as non-terminal nodes. Every non-leaf node is an internal node.

Edge-

The connecting link between any two nodes is called as an edge. In a tree with n number of nodes, there are exactly (n-1) number of edges.

Leaf Node-

The node which does not have any child is called as a leaf node. Leaf nodes are also called as external nodes or terminal nodes.

Height-

Total number of edges that lies on the longest path from any leaf node to a particular node is called as height of that node. Height of a tree is the height of root node. Height of all leaf nodes = 0

Traversals

Unlike linear data structures which have only one logical way to traverse them, trees can be traversed in different ways. Following are the generally used ways for traversing trees.

Depth First Traversals:

(a) Inorder (Left, Root, Right)

(b) Preorder (Root, Left, Right)

(c) Postorder (Left, Right, Root)

Breadth-First or Level Order Traversal
Binary Tree Vs K-Ary Trees

A binary tree for which the root node has no right child, can be viewed as a general tree, and any binary tree can be viewed as a collection (forest) of general trees. A K-ary tree is a tree in which no node can have more than K children. A binary tree is an example of a K-ary tree, where K is 2.
