# Langton-s-Ant-Simulator

This Jupyter Notebook explores the behavior of Langton's Ant, a cellular automaton model exhibiting emergent complexity.

**Functionality:**

* Creates a random grid of black and white squares.
* Simulates the ant's movement based on the following rules:
    * If the ant is on a white square, it turns right, flips the square to black, and moves forward.
    * If the ant is on a black square, it turns left, flips the square to white, and moves forward.
* Tracks the ant's path and updates the grid throughout the simulation.
* Visualizes the final grid state and the ant's path using Matplotlib.

**Code Breakdown:**

* Imports necessary libraries: `matplotlib.pyplot` for visualization, `numpy` for array manipulation, and `random` for grid initialization.
* Defines grid size (`width` and `height`).
* Initializes a random grid (`grid`) of black and white squares (0 and 1).
* Sets the initial ant position (`ant_x`, `ant_y`) and direction (`direction`).
* Implements the simulation loop:
    * Updates the ant's direction and grid based on the current square color.
    * Moves the ant forward based on the direction.
    * Handles boundary conditions (wrapping around the grid).
    * Records the ant's path as a list of coordinates.
* Creates subplots using Matplotlib:
    * Plots the final grid state with a grayscale colormap.
    * Plots the ant's path as a red line on a separate subplot.
* Displays the visualizations.

**Running the Simulation:**

1. Save the Jupyter Notebook as a `.ipynb` file.
2. Open the file in a Jupyter Notebook environment.
3. Run all cells (Kernel -> Run all cells) or press `Shift + Enter` for each cell to execute the code.
4. The output area displays the final grid state and the ant's path.

**Future Enhancements:**

* Explore different initial grid configurations or ant starting positions.
* Modify the simulation rules to observe how variations affect behavior.
* Implement visualization tools to track the grid evolution over time.
* Analyze the ant's path statistically to quantify its complexity.
* Investigate potential applications of Langton's Ant in various fields.
