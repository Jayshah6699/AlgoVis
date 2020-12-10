# Pathfinding-Simulator
This a fun project in which we have made a fun website based on html css and javascript.

This website includes various algorithms like

Dijkstra's Algorithm,
A* Search,
Greedy Best-first Search,
Swarm Algorithm,
Convergent Swarm Algorithm,
Bidirectional Swarm Algorithm,
Breadth-first Search,
Depth-first Search.

some of them are weighted and some of them are unweigted.

This all visualization will be done on grids(kind of graphs).

you can also add weights in weighted algorithms to visualize it more efficiently.

# Meet the Algorithms
This Website supports the following algorithms:

Dijkstra's Algorithm (weighted): the father of pathfinding algorithms; guarantees the shortest path

A* Search (weighted): arguably the best pathfinding algorithm; uses heuristics to guarantee the shortest path much faster than Dijkstra's Algorithm

Greedy Best-first Search (weighted): a faster, more heuristic-heavy version of A*; does not guarantee the shortest path

Swarm Algorithm (weighted): a mixture of Dijkstra's Algorithm and A*; does not guarantee the shortest-path

Convergent Swarm Algorithm (weighted): the faster, more heuristic-heavy version of Swarm; does not guarantee the shortest path

Bidirectional Swarm Algorithm (weighted): Swarm from both sides; does not guarantee the shortest path

Breath-first Search (unweighted): a great algorithm; guarantees the shortest path

Depth-first Search (unweighted): a very bad algorithm for pathfinding; does not guarantee the shortest path

On top of the pathfinding algorithms listed above, I implemented a Recursive Division Maze Generation algorithm.

#  More about the Swarm Algorithm
The Swarm Algorithm is an algorithm that is essentially a mixture of Dijkstra's Algorithm and A* Search; more precisely, while it converges to the target node like A* , it still explores quite a few neighboring nodes surrounding the start node like Dijkstra's.

The algorithm differentiates itself from A* through its use of heuristics: it continually updates nodes' distance from the start node while taking into account their estimated distance from the target node.

This effectively "balances" the difference in total distance between nodes closer to the start node and nodes closer to the target node, which results in the triangle-like shape of the Swarm Algorithm.

The name of algorithm is "Swarm" because of one of its potential applications could be seen in a video-game where a character must keep track of a boss with high priority (the target node), all the while keeping tracking of neighboring enemies that might be swarming nearby.


https://jayshah6699.github.io/Pathfinding-visualizer/

