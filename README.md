# INTERACTIVE-VISUALIZATION-OF-PATHFINDING-ALGO-s
Finding shortest path using dijkstra's algorithm, A* and BFS

Dijkstra's algorithm allows us to find the shortest path between any two vertices of a graph.
It differs from the minimum spanning tree because the shortest distance between two vertices might not include all the vertices of the graph.

![image](https://user-images.githubusercontent.com/85027477/176679296-710946f3-ed4b-4647-ac60-d843bf7d53f3.png)


Djikstra used this property in the opposite direction i.e we overestimate the distance of each vertex from the starting vertex. Then we visit each node and its neighbors to find the shortest subpath to those neighbors.
The algorithm uses a greedy approach in the sense that we find the next best solution hoping that the end result is the best solution for the whole problem.

Example of Dijkstra's algorithm

It is easier to start with an example and then think about the algorithm.
![image](https://user-images.githubusercontent.com/85027477/176679721-75eb1398-c03a-473d-8525-a3cfffe7b0ce.png)


Dijkstra's Algorithm Applications:

To find the shortest path
In social networking applications
In a telephone network
To find the locations in the map
