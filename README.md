# C - Binary Trees Playground

## Welcome!
Welcome to the fascinating world of Binary Trees in C! 🌳 This readme is your guide to understanding, implementing, and mastering the art of binary trees.

## General Objectives

### What is a Binary Tree?
A binary tree is like a family tree for data, where each member (node) can have at most two children. Think of it as a branching structure, with data flowing down from parent to child.

### Binary Tree vs Binary Search Tree
A Binary Search Tree (BST) is like a wise librarian arranging books on shelves. Each book has a unique position, making searching and organizing a breeze compared to a regular binary tree.

### Time Complexity Wins!
Imagine a library where finding a book takes less time than reading the entire collection. That's the beauty of binary trees; they can significantly speed up operations like search, insert, and delete compared to linked lists.

### Tree Metrics: Depth, Height, and Size
- **Depth:** How many generations deep a node is in the tree.
- **Height:** The length of the longest path from a node to a leaf.
- **Size:** The total number of nodes in the tree.

### Traversal Magic
Traverse a binary tree like a forest ranger exploring the woods:
- *In-order:* Wander left, discover the root, explore right.
- *Pre-order:* Start at the root, then venture left and right.
- *Post-order:* Roam left and right before reaching the root.

### Types of Binary Trees
- *Complete:* Picture a seating arrangement in a theater. Every seat in the last row is filled from left to right.
- *Full:* A binary tree where each node is either a leaf or has two children. It's like a puzzle; each piece fits perfectly.
- *Perfect:* The holy grail of balance. All leaf nodes are at the same level, creating a symmetrical masterpiece.
- *Balanced:* A tree where no branch feels heavier than the other, ensuring efficient operations.



### Basic Binary Tree Structure
```c
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;

Binary Search Tree
typedef struct binary_tree_s bst_t;

AVL Tree
typedef struct binary_tree_s avl_t;

Max Binary Heap
typedef struct binary_tree_s heap_t;

