Data Structures & Algorithms in Java
====================================

This repository contains Java implementations of fundamental Data Structures and Algorithms. 
Each program is written in a simple and beginner-friendly way with core operations like insertion, 
deletion, traversal, searching, and sorting.

Contents
--------

Linked Lists
------------
- Linked List (Insertion, Deletion & Display) – A linear data structure where elements (nodes) are connected using pointers. Supports insertion, deletion, and traversal.
- Singly Linked List – Each node contains data and a pointer to the next node. Traversal is only forward.
- Doubly Linked List – Each node has pointers to both the previous and next node, allowing forward and backward traversal.
- Circular Linked List – The last node points back to the first node, forming a circle. Can be singly or doubly linked.
- Problem Statement (1) – Custom problem-solving implementation using linked list operations.
- Problem Statement (2) – Another practical problem solved using linked lists.
- Circular Doubly Linked List – A doubly linked list where the last node connects back to the first node.
- Remove Duplicates from a Sorted Linked List – Algorithm to clean duplicate values while maintaining order.
- Find the Middle Value in a Linked List – Uses slow/fast pointer approach to find the middle efficiently.

Queue
-----
- Queue (Basic Implementation) – A linear data structure following FIFO (First In First Out). Example: waiting line.
- Queue (Finding Head, Size, and Removing Elements) – Operations to check the front element, count size, and dequeue.
- Priority Queue – A queue where each element has a priority, and higher priority elements are served first.
- Queue for String – Queue operations implemented with string data.
- Implementation of Queue using Array – Demonstrates queue operations using a fixed-size array.

Stack
-----
- Stack – A linear data structure following LIFO (Last In First Out). Example: plates stacked in a pile.
- Stack using ArrayDeque – Efficient stack implementation using Java’s ArrayDeque.
- Stack Implementation using Array – Basic stack operations (push, pop, peek) using arrays.
- Reversing a String using Stack – Uses stack’s LIFO property to reverse a string.
- Check Balanced Parentheses – Validates expressions by checking matching brackets using stack.

Sorting Algorithms
------------------
- Selection Sort – Repeatedly selects the smallest element and places it at the correct position.
- Insertion Sort – Builds the sorted list one element at a time by placing each in its correct position.
- Merge Sort – A divide-and-conquer sorting algorithm that splits the array and merges sorted halves.
- Bubble Sort – Repeatedly swaps adjacent elements if they are in the wrong order.
- Quick Sort – A divide-and-conquer algorithm that partitions the array around a pivot and sorts recursively.

Trees
-----
- Binary Search Tree (BST) – A binary tree where the left child is smaller and the right child is larger than the root. Supports fast searching, insertion, and deletion.
- AVL Tree – A self-balancing BST where the height difference of subtrees is at most 1, ensuring O(log n) operations.
- Segment Tree – A tree data structure used for range queries (like sum or min) and updates in O(log n).

Graphs & Algorithms
-------------------
- Dijkstra’s Algorithm (Shortest Path) – Finds the shortest path from a source node to all other nodes in a weighted graph.

How to Run
----------
Clone this repository:

    git clone https://github.com/your-username/dsa-java-codes.git

Open in VS Code, IntelliJ IDEA, or any Java IDE.

Compile and run any program:

    javac FileName.java
    java FileName

Requirements
------------
- Java JDK 8 or later
- Any Java IDE (VS Code / IntelliJ / Eclipse) or terminal
