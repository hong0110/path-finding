# Pathfinding 
This is a visualization tool designed to demonstrate the inner workings of various pathfinding algorithms as they navigate from point A to point B. It also offers an engaging look at different maze/pattern generation algorithms and how they craft intricate mazes/patterns. 


## Pathfinding Algorithms

- **A\*** - A\* pathfinding is a heuristic algorithm that efficiently finds the shortest path from a start to a target node in a graph. It evaluates nodes based on their current cost and an estimated remaining cost to the target.

- **Dijkstra** - Dijkstra's algorithm finds the shortest path from a start node to all other nodes in a weighted graph. It maintains a priority queue of nodes, continually updating the shortest known distance from the start. It explores nodes with the lowest distance first, guaranteeing an optimal path when finished.

## Maze/Pattern Algorithms

- **Recursive Division** - Recursive division maze generation splits a maze into sections with walls, then recursively divides those sections with walls perpendicular to each other, creating a maze pattern. It repeats until the desired level of complexity is achieved, generating intricate mazes.

- **Prims's** - Prim's maze generation begins with a grid of walls. It selects a random starting point and adds it to the maze. Then, it considers neighboring cells that are not yet part of the maze and connects one of them to the existing maze through the shortest available path. This process repeats until all cells are included in the maze, resulting in a maze with a tree-like structure.


## Development
Follow these steps to run the project locally.
1. Clone the repository (HTTPS).
  ```sh
  git clone https://github.com/TylerMommsen/pathfinding-visualizer.git
  ```

2. Navigate to directory
  ```sh
  cd path-finding
  ```

2. Install dependenices
  ```sh
  npm install
  ```

3. Run the project
  ```sh
  npm run dev
  ```
