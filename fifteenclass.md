
## OUR Topic is about Trees , Binary Trees, Binary Search Trees, and K-ary Trees:

![trees](https://amiradata.com/wp-content/uploads/2020/05/tree-data-structure-1024x718.png)

## What is TREEs:

-They are as I understood are node based data structures.
- They consisit from nodes that are referring to other number of nodes , we can say they have like parent node that refer to other children nodes which can be 2 children nodes (binary tree) or k number of nodes (K-ary Trees)


## How to move throgh the tree nodes ?

- Traversals has two ways in trees :

- Depth First(height)

    - Pre-order: root >> left >> right
    - In-order: left >> root >> right
    - Post-order: left >> right >> root

- The most common way to traverse through a tree is to use recursion

- The biggest difference between each of the traversals is **when you are looking at the root node.**

- Breadth first (width);

- Breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree.

## Binary Tree Vs K-ary Trees:

- AS I have mentioned Trees can have any number of children per node, but Binary Trees restrict the number of children to two.

## K-ary Trees:

-In this type of tree we use K to refer to the maximum number of children that each Node is able to have.

### Breadth First Traversal:

- Traversing a K-ary tree requires a similar approach to the breadth first traversal. 
- We are still pushing nodes into a queue

## How to tell where I can add a new node?

- Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node gets placed.

>One strategy for adding a new node to a binary tree is to fill all “child” spots from the top down
> In the event you would like to have a node placed in a specific location, you need to reference both the new node to create, and the parent node upon which the child is attached to.

## Big O

- The Big O time complexity for inserting a new node is O(n).

> A “perfect” binary tree is one where every non-leaf node has exactly two children. The maximum width for a perfect binary tree, is 2^(h-1), where h is the height of the tree. Height can be calculated as log n, where n is the number of nodes.

## Binary Search Trees;

- Nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

### Searching a BST

- Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.

### Big O:
- The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height)

-The Big O space complexity of a BST search would be O(1)