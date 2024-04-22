# Combined README for Project 1 and Project 2

## Project 1: Traveling Salesman Problem (TSP) using Genetic Algorithm

### Overview
Project 1 implements a Genetic Algorithm (GA) to solve the Traveling Salesman Problem (TSP). The goal is to find the shortest possible route that visits a set of cities and returns to the origin city.

### Implementation
The implementation includes a class `City` to represent each city with coordinates, a `CityPosition` class to manage the cities, and a `GeneticAlgorithm` class to perform the evolution process. The TSP class plots the best route and fitness curve over the generations.

### Usage
To run the project, execute the main block in the `project1.py` file. The output will be a graphical representation of the best route and a fitness curve showing the optimization progress.

---

## Project 2: Constrained Optimization using Genetic Algorithm

### Overview
Project 2 uses a Genetic Algorithm to optimize a cost function with inequality constraints. The solution is evolved over several generations to minimize the cost function.

### Objective Function and Constraints
The optimization problem includes a cost function and constraints related to variables `x1` to `x4`.

### Implementation
A `Member` class represents a potential solution, and the GA evolves a population of these members. The `cost_function` handles the calculation of cost and constraint violation. The solution process involves crossover and mutation operations.

### Usage
Run the `project2.py` file to execute the optimization process. The results are visualized with a plot showing the inverted cost function values over iterations, indicating the optimization progress.

---

### Visualizations

#### GA Optimization Progress (Project 2)
![GA Optimization Progress](GAOptimizationProgess(project2).jpg)

#### Boiler Mathematical Formulation (Project 2)
![Boiler Mathematical Formulation](BoilerMath(project2).jpg)

---

### Notes
- Ensure you have all the required libraries installed before running the projects.
- Modify the parameters in the code for different experimentations.