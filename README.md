# Traveling Salesman Problem: Single vs. Population-Based Search

## Overview  
This project explores solving the Traveling Salesman Problem (TSP) using four algorithms: Hill Climbing, Simulated Annealing, Tabu Search, and Genetic Algorithm. The TSP requires finding the shortest route visiting all cities once and returning to the start.

## Objectives  
- Implement and evaluate three single-solution search algorithms (Hill Climbing variants, Simulated Annealing, Tabu Search).  
- Identify the best-performing single-solution algorithm.  
- Compare it with a population-based Genetic Algorithm across different problem sizes (10 to 50 cities).  
- Analyze performance based on solution quality and computational efficiency.  
- Conduct statistical tests to validate results and provide recommendations.

## Methodology  
1. **Data Preparation:** Use datasets for city sizes 10, 20, 30, 40, and 50.  
2. **Algorithm Implementation:**  
   - Hill Climbing (Standard, Steepest-Ascent, Stochastic)  
   - Simulated Annealing (with various cooling schedules)  
   - Tabu Search (using memory to avoid revisits)  
   - Genetic Algorithm (population-based)  
3. **Evaluation:** Compare algorithms by solution quality, runtime, and convergence behavior.  
4. **Visualization:** Graph results for clear performance comparisons.  
5. **Discussion:** Explain findings and recommend algorithms based on problem scale.

## Results  
The project identifies which single-solution search algorithm performs best and compares it against the Genetic Algorithm, highlighting trade-offs between solution quality and efficiency.

## Usage  
Clone this repository, run the Jupyter Notebook to explore implementations, visualizations, and analyses.

## References  
- Module materials on TSP and algorithms  
- Relevant academic papers and algorithm descriptions  
