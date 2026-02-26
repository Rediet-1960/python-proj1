# Shortest Path Python Project

This repository contains a simple Python script demonstrating how to compute the shortest paths in a graph using Dijkstra's algorithm. It was created as a small learning project and includes:

- `shortese path.py/shortest path` - the main Python script defining a graph and computing shortest distances and paths from a given start node.

## Usage

Run the script with a Python interpreter (e.g., `python "shortese path.py/shortest path"`). By default, it computes shortest paths from node `A` to all other nodes in a hard-coded graph and prints the results.

You can modify the `my_graph` dictionary and the call to `shortest_path()` to experiment with different graphs or starting/target nodes.

## Graph Format

The graph is represented as a dictionary mapping each node to a list of tuples `(neighbor, weight)`.

## Example Output

```
A-B distance: 5
Path: A -> B

A-C distance: 3
Path: A -> C

... etc.
```

## License

This project is provided for educational purposes and is unlicensed. Feel free to copy and modify the code as needed.
