# Search Algorithms Visualizer

## Overview
This Python application provides a graphical interface for visualizing various searching algorithms on a graph. Users can create a custom graph, add vertices, edges, and weights, or use a predefined sample graph. The implemented searching algorithms include Breadth-First Search (BFS) and Depth-First Search (DFS).

## Features
- **Graph Creation:**
  - Add vertices to the graph.
  - Connect vertices with edges and specify weights.
  - Visualize the graph in real-time.

- **Predefined Sample Graph:**
  - Create a sample graph with predefined vertices, edges, and weights.

- **Searching Algorithms:**
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)

- **Algorithm Visualization:**
  - Visualize the traversal process of the selected algorithm on the graph.
  - Control the speed of traversal.

## How to Use
1. **Run the Application:**
   - Save the provided code to a file, for example, `search_visualizer.py`.
   - Open a terminal or command prompt, navigate to the directory containing the file, and run the following command:

     ```bash
     python ac.py
     ```

2. **Graph Creation:**
   - Use the text entry to add vertices to the graph.
   - Connect vertices with edges and specify weights.
   - Visualize the graph using the "Add Vertex," "Add Edges," and "Add Weights" buttons.

3. **Predefined Sample Graph:**
   - Click the "Create Sample Graph" button to generate a predefined sample graph.

4. **Searching Algorithms:**
   - Choose a searching algorithm from the options (BFS, DFS).
   - Enter the goal and starting nodes as required.
   - Adjust the traversal speed using the "Traversal Speed" input.

5. **Run the Algorithm:**
   - Click the "Run BFS" or "Run DFS" button to visualize the algorithm's traversal on the graph.

6. **Algorithm Visualization:**
   - Observe the real-time visualization of the algorithm's traversal on the graph.
   - The traversed path is displayed below the visualization.

7. **Experiment and Explore:**
   - Add your custom graphs, weights, and try different searching algorithms.
   - Experiment with traversal speeds to observe the algorithm's behavior.

8. **Dependencies:**
   - The application relies on the `networkx`, `matplotlib`, and `tkinter` libraries. Install them using:

     ```bash
     pip install networkx matplotlib
     ```
