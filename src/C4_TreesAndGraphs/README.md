[**4.1 Route Between Nodes:**](P1_RouteBetweenNodes.java) Given a directed graph, design an algorithm to find out whether there is a route between two nodes.\
\
[**4.2 Minimal Tree:**](P2_MinimalTree.java) Given a sorted (increasing order) array with unique integer elements, write an algorithm to create a binary search tree with minimal height.\
\
[**4.3 List of Depths:**](P3_ListOfDepths.java) Given a binary tree, design an algorithm which creates a linked list of all the nodes at each depth (e.g., if you have a tree with depth 0, you'll have 0 linked lists).\
\
[**4.4 Check Balanced:**](P4_CheckBalanced.java) Implement a function to check if a binary tree is balanced. For the purposes of this question, a balanced tree is defined to be a tree such that the heights of the two subtrees of any node never differ by more than one.\
\
[**4.5 Validate BST:**](P5_ValidateBST.java) Implement a function to check if a binary tree is a binary search tree.\
\
[**4.6 Successor:**](P6_Successor.java) Write an algorithm to find the "next" node (i.e., in-order successor) of a given node in a binary search tree. You may assume that each node has a link to its parent.\
\
[**4.7 Build Order:**](P7_BuildOrder_Author) You are given a list of projects and a list of dependencies (which is a list of pairs of projects, where the second project is dependent on the first project). All of a project's dependencies must be built before the project is. Find a build order that will allow the projects to be built. If there is no valid build order, return an error.\
EXAMPLE\
Input:\
projects: a, b, c, d, e, f dependencies: (a, d), (f, b), (b, d), (f, a), (d, c)\
Output: f, e, a, b, d, c\
\
[**4.8 First Common Ancestor:**](P8_FirstCommonAncestor.java) Design an algorithm and write code to find the first common ancestor of two nodes in a binary tree. Avoid storing additional nodes in a data structure. NOTE: This is not necessarily a binary search tree.\
\
[**4.9 BST Sequences:**](P9_BSTSequence.java) A binary search tree was created by traversing through an array from left to right and inserting each element. Given a binary search tree with distinct elements, print all possible arrays that could have led to this tree\
\
[**4.10 Check Subtree:**](P10_CheckSubtree.java) Tl and T2 are two very large binary trees, with Tl much bigger than T2. Create an algorithm to determine if T2 is a subtree of Tl. A tree T2 is a subtree ofTi if there exists a node n in Ti such that the subtree of n is identical to T2. That is, if you cut off the tree at node n, the two trees would be identical.\
\
[**4.11 Random Node:**](P11_RandomNode_Author) You are implementing a binary tree class from scratch which, in addition to insert, find, and delete, has a method getRandomNode() which returns a random node from the tree. All nodes should be equally likely to be chosen. Design and implement an algorithm for getRandomNode, and explain how you would implement the rest of the methods.\
\
[**4.12 Paths with Sum:**](P12_PathsWithSum_Author) You are given a binary tree in which each node contains an integer value (which might be positive or negative). Design an algorithm to count the number of paths that sum to a given value. The path does not need to start or end at the root or a leaf, but it must go downwards (traveling only from parent nodes to child nodes).