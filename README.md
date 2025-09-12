### Data Structures & Algorithms in Java

- This repository contains Java implementations of fundamental Data Structures and Algorithms.
Each program is written in a simple and beginner-friendly way with core operations like insertion, deletion, traversal, searching, and sorting.

## Linked List and Queue


i. What is a Queue?
- A: A queue is a linear data structure that follows the FIFO (First In, First Out) principle. The element inserted first is the first to be removed. Example: a line of people waiting at a ticket counter.




ii. What is a Singly Linked List?
- A: A singly linked list is a linear data structure where each node contains data and a pointer to the next node. Traversal is only possible in one direction (forward).



iii. What is a Doubly Linked List?
- A: A doubly linked list is a linked list where each node contains data, a pointer to the next node, and a pointer to the previous node. It allows traversal in both directions (forward and backward).




iv. What is a Circular Singly Linked List?
- A: A circular singly linked list is a variation of a singly linked list where the last node points back to the first node, forming a circle. Traversal can loop infinitely unless stopped.




v. What is a Circular Doubly Linked List?
- A: A circular doubly linked list is a variation of a doubly linked list where the last node connects back to the first node, and the first node’s previous pointer points to the last node. Traversal is possible in both directions in a circular manner.


---
### Stack
- Stack :- A linear data structure following LIFO (Last In First Out). Example: plates stacked in a pile.
- Stack using ArrayDeque :- Efficient stack implementation using Java's ArrayDeque.
- Stack Implementation using Array :- Basic stack operations (push, pop, peek) using arrays.
- Reversing a String using Stack :- Uses stack's LIFO property to reverse a string.
- Check Balanced Parentheses :- Validates expressions by checking matching brackets using stack.

---

### Sorting Algorithms
- Selection Sort :- Repeatedly selects the smallest element and places it at the correct position.
- Insertion Sort :- Builds the sorted list one element at a time by placing each in its correct position.
- Merge Sort :- A divide-and-conquer sorting algorithm that splits the array and merges sorted halves.
- Bubble Sort :- Repeatedly swaps adjacent elements if they are in the wrong order.
- Quick Sort :- A divide-and-conquer algorithm that partitions the array around a pivot and sorts recursively.

---

### Trees
- Binary Search Tree (BST) :- A binary tree where the left child is smaller and the right child is larger than the root. Supports fast searching, insertion, and deletion.
- AVL Tree :- A self-balancing BST where the height difference of subtrees is at most 1, ensuring O(log n) operations.
- Segment Tree :- A tree data structure used for range queries (like sum or min) and updates in O(log n).

---

### Graphs & Algorithms
- Dijkstra's Algorithm (Shortest Path) :- Finds the shortest path from a source node to all other nodes in a weighted graph.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Itachi-maker/DSA-Placements-Java-.git
   ```
2. Open in VS Code, IntelliJ IDEA, or any Java IDE.  
3. Compile and run any program:
   ```bash
   javac FileName.java
   java FileName
   ```

---

## Requirements
- Java JDK 8 or later  
- Any Java IDE (VS Code / IntelliJ / Eclipse) or terminal 
