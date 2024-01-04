# Binary Trees - Overview

## What is a Binary Tree?
A binary tree is a hierarchical data structure composed of nodes, where each node can have at most two children. The tree starts from a root node, and every node can have a left child and a right child. The children of a node are referred to as its left subtree and right subtree, respectively. Each node in a binary tree can be considered as the root of its own subtree.

## Binary Tree vs. Binary Search Tree
While a binary tree is a general tree structure, a Binary Search Tree (BST) is a specific type of binary tree. The main difference between the two is that in a BST, the values of the nodes follow a specific order. The left child of a node must have a value less than the node itself, while the right child must have a value greater than the node. This ordering property makes searching, insertion, and deletion operations more efficient in a BST compared to a general binary tree.

## Time Complexity Compared to Linked Lists
In terms of time complexity, binary trees offer significant advantages over linked lists for certain operations. The time complexity for searching, inserting, and deleting elements in a binary tree is typically O(log n), where n is the number of elements in the tree. This efficiency is achieved because binary trees are structured in a way that allows for effective binary search algorithms. In contrast, linked lists have a time complexity of O(n) for these operations since they require linear traversal of the list.

## Depth, Height, and Size of a Binary Tree
- **Depth**: The depth of a node in a binary tree represents the number of edges from the root node to that particular node. The depth of the root node is 0, and it increases by 1 as we move down the tree.
- **Height**: The height of a binary tree is the maximum depth among all its nodes. It represents the length of the longest path from the root node to any leaf node.
- **Size**: The size of a binary tree refers to the total number of nodes present in the tree.

## Traversal Methods for Binary Trees
There are several common methods to traverse a binary tree:
- **In-order traversal**: In this traversal, the left subtree is visited first, followed by the root node, and then the right subtree.
- **Pre-order traversal**: In this traversal, the root node is visited first, followed by the left subtree, and then the right subtree.
- **Post-order traversal**: In this traversal, the left subtree is visited first, followed by the right subtree, and finally the root node.
- **Level-order traversal**: This traversal visits the nodes at each level of the binary tree from left to right, starting from the root and moving down to the deepest level.

## Types of Binary Trees
- **Complete Binary Tree**: A complete binary tree is a binary tree in which all levels, except possibly the last one, are completely filled, and all nodes are as left as possible.
- **Full Binary Tree**: A full binary tree is a binary tree in which every node has either 0 or 2 children. There are no nodes with only one child.
- **Perfect Binary Tree**: A perfect binary tree is both complete and full. It is a binary tree in which all internal nodes have two children, and all leaf nodes are at the same level.
- **Balanced Binary Tree**: A balanced binary tree is a binary tree in which the heights of the left and right subtrees of any node differ by at most one.

---

This document provides a basic understanding of binary trees, including their structure, differences from Binary Search Trees, time complexity advantages over linked lists, characteristics such as depth, height, and size, traversal methods, and types of binary trees.
