

### **Genetic Algorithm Project**

**Objective**:
- The goal of this project is to implement the genetic algorithm to solve two optimization tasks: 
  1. Optimize a continuous function.
  2. Solve the Traveling Salesman Problem (TSP).

**Team**:
- Work in teams of 3-4 students to develop and implement the genetic algorithm and solve the assigned tasks.

### **Task 1: Optimize a Continuous Function**
- **Unconstrained Optimization**: 
  - Objective: Minimize the function ( f(x) = 2x^4 - 10x^2 + 8x + 5 ) within the range (-5 <= x <= 5).
  - Deliverables: Plot the objective function, choose user-defined parameters (like the crossover rate), design a stopping criterion, and report the optimal design variable and solution.
  
- **Constrained Optimization**: 
  - Objective: Minimize the function with the constraint ( x <= 2 ).
  - Deliverables: Plot both the objective function and the constraint, explain how the constraint is considered in the genetic algorithm, and report the optimal design variable and solution.
  - Comparison of the constrained vs. unconstrained optimal points and an explanation of the differences.

### **Task 2: Solve the Traveling Salesman Problem (TSP)**
- **Problem Statement**: 
  - You are tasked with finding the shortest route for UPS truck drivers across seven cities (Atlanta, Boston, Cincinnati, Denver, New York, Philadelphia, San Francisco). 
  - The objective is to determine the shortest delivery route that visits each city exactly once starting from Atlanta.
  
- **Deliverables**:
  1. Generate a plot showing the delivery locations for the selected cities.
  2. Construct a distance adjacency matrix using the Haversine formula to calculate the great circle distances between cities.
  3. Find the shortest route using a **greedy algorithm** (nearest neighbor selection) and provide a plot of the optimized route.
  4. Find the shortest route using the **genetic algorithm**, report the optimal route and value, and provide a plot of the optimized route.
  5. Compare and explain the differences between the solutions from the greedy and genetic algorithms.
  6. Plot the convergence history of the genetic algorithm to show the optimum value over iterations.
  7. Discuss whether the solution from the genetic algorithm is a global optimum.
  8. Discuss the variability of solutions when executing the algorithm multiple times.
  9. Explore strategies for improving the computational efficiency of the algorithm, particularly when using the greedy algorithm.



### **A-star Algorithm Project**

**Objective**:
- The goal of this project is to implement a graph-based pathfinding algorithm (A*) for flight path optimization, focusing on two conditions: clear weather and severe weather.

**Team**:
- The project will be carried out in teams of 2-3 students, with a focus on dividing tasks equally. The team is required to submit a report and simulation code.

### **Task: Flight Path Optimization Using A-star Algorithm**
- **Problem Statement**: 
  - As a flight dispatcher for Korean Airlines, you are tasked with planning the most efficient route for a pilot traveling from Jeju International Airport to Gimpo International Airport. The pilot requests two options: 
    1. The shortest path under clear weather conditions.
    2. The shortest path under severe weather conditions.

- **Deliverables**:
  - **Graph Representation**: Define how to represent the graph for the flight path optimization problem.
  - **Weight Values**: Estimate the weight values for the edges in the graph, reflecting real-world conditions.
  - **Shortest Path**: Use the A* algorithm to find the shortest path for both clear and severe weather conditions.
  - **Comparison of Paths**: Discuss whether the shortest paths are the same for both weather conditions and provide reasons for any differences.
  - **Severe Weather Impact**: Incorporate severe weather conditions into the algorithm. The weather is modeled with polygon information that restricts certain areas from being visited.
  - **Global Optimum**: Consider if the shortest path found by your algorithm represents a global optimum.
  - **Pseudo Code**: Provide a step-by-step explanation of the pseudo code used to implement the solution.

- **Weather Conditions**: 
  - Severe weather is modeled using a polygon that defines a restricted area: 
    
    Polygon = ([ (126.4, 34.6), (127.1, 34.6), (127.1, 34.2), (126.4, 34.2) ]
    
  
- **Graph Structure**: 
  - The provided graph structure, **Korean Airways**, must be used for this project, and no alternative graph structures are allowed.

