# AntPathFinding
MATLAB simulation that mimics how ants find the shortest path between two points

# Simulation
Two points are randomly generated and a number of random paths between the two points are generated. At each step, pheromones are deposited which is accumulated in a 2d array.

When looking for the shortest path, each ant detects pheromone concentration on a local level. It compares the pheromone concentrations in the 4 cardinal directions and moves towards the highest pheromone concentration when moving from the food back to the nest and moves towards the lowest concentration when moving from the nest towards food. 

As the number of paths between the food and nest increases, the "shortest path" between the points becomes better and better.

Although this simulation is on a 2d grid and ants are only allowed to move in the cardinal directions, it shows how simply ant behavior can lead to quickly finding the shortest path between poitns

# Applications
This type of problem is seen in everyday life from finding the most efficient route when driving, mapping airplane routes, and finding the best path when conducting mail deliveries. 
