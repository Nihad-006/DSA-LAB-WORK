Graphs

This directory contains C and C++ implementations of fundamental graph data structures and algorithms. It provides a practical exploration of how graphs can be represented in memory and how different graph algorithms can be used for traversal, shortest-path finding, and minimum spanning tree problems.

📂 Repository Contents

1. Graph Representations (Data Structures)

These files demonstrate different approaches to storing graph data in memory. The choice of representation depends on the graph density and the operations that need to be performed efficiently.

- AdjacencyMatrix.c
  Implements a graph using a 2D array (matrix). It provides fast edge lookups and is particularly suitable for dense graphs. However, it requires O(V²) space.

- AdjacencyList.c
  Implements a graph using an array of linked lists. It is more space-efficient for sparse graphs, requiring O(V + E) space. It also allows efficient traversal of the neighbors of a vertex.

- EdgeList.c
  Represents a graph as a simple list or array of edges. This representation is straightforward and is commonly useful for algorithms such as Kruskal’s Algorithm.

2. Graph Algorithms

These files contain implementations of important graph algorithms used for solving common graph-related problems.

- dijkstras.cpp
  Implements Dijkstra’s Algorithm, which finds the shortest paths from a single source vertex to all other vertices in a weighted graph with non-negative edge weights.

- kruskal.cpp
  Implements Kruskal’s Algorithm, a greedy algorithm used to find the Minimum Spanning Tree (MST) of a connected, undirected, weighted graph. It selects edges in increasing order of weight while avoiding cycles.

🎯 Purpose of the Lab

The main objective of this lab is to understand:

1. Different methods of graph representation.
2. The advantages and limitations of each representation.
3. Shortest-path algorithms, particularly Dijkstra’s Algorithm.
4. Minimum Spanning Tree construction using Kruskal’s Algorithm.
5. The practical implementation of graph concepts using C and C++.
