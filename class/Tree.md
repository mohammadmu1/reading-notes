# Types of Trees

- Trees have nodes with values and references to other nodes.
- The starting node is called the root.
- Binary trees have at most 2 children per node (left and right).
- Each connection between parent and child is called an edge.
- A node with no children is called a leaf.
- The height of a tree is the number of edges from the root to the farthest leaf.

# Traversing Trees

- Traversal means visiting each node in a specific order.
- Two categories: Depth First and Breadth First.
- Depth First: Go deep before wide.
- Three methods: Pre-order (root, left, right), In-order (left, root, right), Post-order (left, right, root).
- Breadth First: Visit each level before going deeper.



# Adding a Node

- Use breadth-first traversal to find the first node with an available child slot.
- Insert the new node as a child.

# Big O Complexity

- Insertion and searching in Binary Trees is O(height).
- In a balanced tree, height is log(n).
- In an unbalanced tree, height is n.

# Binary Search Trees (BST)

- Organized structure: Left child < Root < Right child.
- Searching in a BST is efficient as you compare and follow the path left or right based on the value you're looking for.

# BST Search

- Compare the target value with the root.
- If smaller, go left; if larger, go right.
- Continue until you find a match or reach a leaf node.

# Big O Complexity for BST

- Search and insertion: O(height), where height is log(n) in balanced trees or n in unbalanced trees.
- Space complexity: O(1) for search.
