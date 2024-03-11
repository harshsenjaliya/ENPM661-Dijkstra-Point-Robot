# ENPM661-Dijkstra-Point-Robot

This Python script implements a path planning algorithm to find the shortest path between two points in a given environment. The environment is represented as a grid map with obstacles, and the algorithm uses A* search to navigate through it.

## Dependencies

- `numpy` for numerical computations
- `matplotlib` for visualization

## Usage

1. Clone the repository:

```bash
git clone https://github.com/harshsenaliya4433/ENPM661-Dijkstra-Point-Robot/tree/main
```
2. Navigate to the project directory:
```bash
cd ENPM661-Dijkstra-Point-Robot
```
3. Run the script:
```bash
enpm661_project_2.py
```
## Algorithm Overview

The algorithm works as follows:

Define a grid map representing the environment with obstacles.
Create a start and goal vertex with their coordinates.
Implement Dijkstra search algorithm to find the shortest path.
Plot the explored vertices and the final path on the grid map.

## Sample Input
You'll be prompted to enter the start and goal coordinates. For example:
```bash
Enter Start X: 10
Enter Start Y: 20
Enter Goal X: 1150
Enter Goal Y: 250
```

## Output

The script will output the following:

1. Visualization of the explored vertices and final path on the grid map.
2.Cost of the shortest path.
3. Execution time of the program.
