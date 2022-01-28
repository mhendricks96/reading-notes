# Reading 15

## Trees

- the root is the top node of a tree

- a leaf is a node with no children

- height is the number of edges below a node

- depth is the number of edges above a node

- every child has only 1 parent

- A tree is a recursive data structure

- every parent node is the root of its own subtree

### Binary Trees

- nodes can have at most 2 chilren

- full binary tree: every node has either 0 or 2 children

- complete binary node: all levels except last are completely filled and the last is filled left to right

- perfect binary tree: all internal nodes contain 2 children and all leaf nodes have no children

- balanced binary tree: height of ef subtrees are all within 1

- pathological/degenerat binary tree: every parent node has only 1 child node

#### Binary Search Trees

- the left subtree of a node contains only nodes with values less than nodes value

the right subtree of a node contains only nodes with values greater than node's value

- left and right of every node is also a binary search tree

#### Traversal

- pre-order: root >> left >> right

- In-order: left >> root >> right

- Post-order: left >> right >> root
