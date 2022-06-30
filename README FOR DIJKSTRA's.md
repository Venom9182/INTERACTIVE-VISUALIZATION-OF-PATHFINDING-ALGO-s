# INTERACTIVE-VISUALIZATION-OF-PATHFINDING-ALGO-s
Finding shortest path using dijkstra's algorithm, A* and BFS

***OUR TASK IS TO CREATE OBSTACLES BETWEEN THE STARTING POINT AND THE DESTINATION TO SEE HOW DIJKSTRA's ALGO FINDS THE SHORTEST PATH BETWEEN THEM.

Dijkstra's algorithm allows us to find the shortest path between any two vertices of a graph.
It differs from the minimum spanning tree because the shortest distance between two vertices might not include all the vertices of the graph.

![image](https://user-images.githubusercontent.com/85027477/176679296-710946f3-ed4b-4647-ac60-d843bf7d53f3.png)


Djikstra used this property in the opposite direction i.e we overestimate the distance of each vertex from the starting vertex. Then we visit each node and its neighbors to find the shortest subpath to those neighbors.
The algorithm uses a greedy approach in the sense that we find the next best solution hoping that the end result is the best solution for the whole problem.

Example of Dijkstra's algorithm

It is easier to start with an example and then think about the algorithm.
![image](https://user-images.githubusercontent.com/85027477/176679721-75eb1398-c03a-473d-8525-a3cfffe7b0ce.png)

![image](https://user-images.githubusercontent.com/85027477/176681634-bffe4dd7-1152-475a-acf0-8b49e70efad3.png)

![image](https://user-images.githubusercontent.com/85027477/176681648-ed2f3f07-f4df-467b-a022-cff208841096.png)

![image](https://user-images.githubusercontent.com/85027477/176681671-19b4a54f-157c-43b0-b0ce-da5e01d12532.png)

![image](https://user-images.githubusercontent.com/85027477/176681684-bb8a1d9f-49fd-4597-b637-bfa87da5bd0c.png)

![image](https://user-images.githubusercontent.com/85027477/176681719-c232404f-25e0-489c-8199-62cfc657afbe.png)

![image](https://user-images.githubusercontent.com/85027477/176681746-6e8fc542-0668-48ea-ac0a-d58eb0124841.png)

![image](https://user-images.githubusercontent.com/85027477/176681758-4ea49aa0-6040-4755-b985-9873a96f7bd7.png)

SCREENSHOT OF WORKING ALGORITHM

![image](https://user-images.githubusercontent.com/85027477/176682443-f0f8f623-2941-40a1-bb59-b0e783c63e75.png)

Dijkstra's Algorithm Applications:

To find the shortest path
In social networking applications
In a telephone network
To find the locations in the map
