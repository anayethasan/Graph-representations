# Graph-representations
Introduction to Algorithms
An algorithm is a sequence of steps or instructions designed to solve a problem. It provides a systematic method to perform tasks or calculations.

What is a Graph?
A graph is a collection of nodes (vertices) connected by edges. It is widely used to represent real-world systems that consist of interconnected entities.

Real-World Applications of Graphs:
Social Networks: Graphs are used to model relationships between users (nodes) and their connections (edges).
Maps and Navigation: Graphs represent locations (nodes) and paths (edges) for navigation systems.
Computer Networks: Nodes represent devices, and edges represent communication links between them.
Recommendation Systems: Used in systems like Netflix or Amazon, where nodes represent items and edges represent relationships based on user preferences.
Graph Input Representation:
Edge List: An edge list is a collection of pairs, where each pair represents an edge that connects two nodes. Example:

(a, b)
(b, c)
(c, d)
Adjacency Matrix: This is a 2D array where both rows and columns represent nodes, and each cell indicates the presence (or absence) of an edge between the nodes.

If matrix[i][j] is 1, there is an edge between node i and node j. If it’s 0, no edge exists between them.
Differences Between Trees and Graphs:
A tree is a special type of graph that has no cycles and has exactly one path between any two nodes.
A graph may have cycles and multiple paths between nodes.
Types of Graphs:
Undirected Graph: The edges do not have a direction; the connection between nodes is bidirectional.
Directed Graph (Digraph): Each edge has a direction, represented as a one-way connection between nodes.
Weighted Graph: Edges have weights associated with them, often representing distances, costs, or other metrics.
Unweighted Graph: All edges are equal, with no weights.
Cyclic Graph: A graph that contains at least one cycle.
Acyclic Graph: A graph that does not contain any cycles.
