File System Representation and Search Using BFS and DFS

1. Project Description

This project implements a file system representation using a graph data structure in C. Each file or directory is represented as a node, and the connections between them are represented as edges. An adjacency matrix is used to store the graph.

The program implements Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms to search for a specified file from a given starting node.

2. Objectives

- Represent a file system using a graph.
- Implement an adjacency matrix.
- Perform BFS traversal to search for a target file.
- Perform DFS traversal to search for a target file.
- Display traversal order and whether the target file is found.

3. Technologies Used

- Programming Language: C
- Data Structure: Graph
- Graph Representation: Adjacency Matrix
- Algorithms: BFS and DFS

4. Features

- Accepts the number of files or directories as input.
- Accepts an adjacency matrix to represent connections.
- Allows the user to select a starting node and target node.
- Displays BFS and DFS traversal orders.
- Reports whether the target node is found by each algorithm.

5. How to Compile and Run

1. Save the program as "main.c".

2. Compile the program using GCC:
   
   gcc main.c -o main

3. Run the program:
   
   ./main
   
   On Windows, use:
   
   main.exe

6. Sample Input

4
0 1 1 0
1 0 0 1
1 0 0 1
0 1 1 0
0
3

7. Sample Output

BFS Traversal: 0 1 2 3
File found using BFS.
DFS Traversal: 0 1 3 2
File found using DFS.

8. Algorithms Used

Breadth-First Search (BFS)

BFS visits nodes level by level using a queue. It explores adjacent nodes before moving to the next level.

Depth-First Search (DFS)

DFS explores a path as deeply as possible before backtracking. This implementation uses recursion.

9. Applications

- File and directory navigation.
- Graph traversal and searching.
- Network connectivity analysis.
- Learning fundamental graph algorithms.

10. Conclusion

This project demonstrates how graphs can represent file system connections and how BFS and DFS can be used to search the graph. It provides a simple practical application of graph data structures and traversal algorithms in C.

Author

Name: Faris N
Department: CSE / DS / CY
Activity: Challenge 17 – B09
