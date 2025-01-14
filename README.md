# Maze Solver with Dijkstra's Algorithm

This project implements a maze solver using Dijkstra's algorithm. The maze is represented as a 2D grid where `0` indicates a walkable path and `1` indicates a wall. The program visualizes the pathfinding process using Matplotlib.

## Features

- Visual representation of the maze and the pathfinding process.
- Implementation of Dijkstra's algorithm to find the shortest path from a start point to an end point in the maze.
- Interactive plotting that shows the exploration of nodes and the final path.

## Requirements

To run this project, you need to have Python installed along with the following libraries:

- `matplotlib`
- `numpy` (optional, depending on your implementation)

You can install the required libraries using pip:


## Usage

1. Clone this repository:


2. Open the Python script in your favorite code editor.

3. Modify the `maze` variable to change the maze layout. The maze is defined as a list of lists, where `0` represents open paths and `1` represents walls.

4. Set the `start` and `end` variables to define the starting and ending points in the maze (in "row,column" format).

5. Run the script:


6. The program will display a plot showing the maze and visualize the pathfinding process.

## Example Maze

The default maze provided in this script is as follows:
maze = [
    [0, 0, 1, 0, 0, 1, 0, 1, 0, 0],
    [1, 0, 1, 1, 0, 1, 0, 1, 0, 1],
    [0, 0, 0, 0, 0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 1, 1, 1, 0, 1],
    [0, 0, 0, 0, 0, 0, 1, 0, 0, 0],
    [0, 1, 1, 1, 1, 0, 1, 1, 0, 1],
    [0, 0, 0, 0, 1, 0, 0, 0, 0, 1],
    [1, 1, 1 ,0 ,1 ,1 ,1 ,0 ,1 ,1],
    [0 ,0 ,0 ,0 ,0 ,0 ,0 ,0 ,0 ,0]
]

## Visualization

The visualization shows:
- **Blue dots** for visited nodes.
- **Cyan lines** for paths being explored.
- A **green triangle** for the starting point.
- A **red triangle** for the ending point.
- The final path is highlighted in **red**.

## Contributing

Feel free to fork this repository and submit pull requests if you have improvements or additional features in mind!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
