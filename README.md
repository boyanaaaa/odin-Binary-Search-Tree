# odin-Binary-Search-Tree
 Binary Search Tree data structure in Javascript

Binary Search Tree data structure in Javascript. A tree is a collection of nodes connected by some edges. A tree is a non linear data structure. A Binary Search tree is a binary tree in which nodes that have lesser value are stored on the left while the nodes with a higher value are stored at the right.


*insert(data) - It creates a new node with a value data, if the tree is empty it add this node to a tree and make it a root, otherwise it calls insert(node, data).
*insert(node, data) - It compares the given data with the data of the current node and moves left or right accordingly and recur until it finds a correct node with a null value where new node can be added.
*remove(data) - It is helper methods which call removeNode by passing root node and given data and updates the root of the tree with the value returned by the function
*removeNode(node, data) - It searches for a node with a given data and then perform certain steps to delete it.
