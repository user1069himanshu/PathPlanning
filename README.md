"Path Planning" is a project that utilizes the A* algorithm to determine the shortest path between two points in a grid-based environment.
The project takes a pixelated image as input and converts it into a grid representation for pathfinding purposes.

The A* algorithm uses a heuristic function to estimate the cost of reaching the goal from the current node and selects the node with the lowest estimated cost.
By implementing the A* algorithm, the project efficiently explores the grid, considering both the distance to the destination and the estimated cost to reach it.
This allows the algorithm to intelligently navigate the grid, avoiding obstacles or restricted areas while finding the optimal path between the given start and end points.

The pixelated image serves as the basis for creating the grid. Each pixel corresponds to a cell in the grid, with specific properties assigned to different types of pixels.
Obstacles or walls may be marked as impassable cells, while open areas are designated as traversable cells. By converting the image into a grid, the project enables accurate path planning and obstacle avoidance.
