---
type: introduction
---

# Traveling Salesman Problem

The traveling salesman problem (TSP) asks the question, "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?".

### This project

- The goal of this site is to help visualize and develop Miller-Tucker-Zemlin formulation, and comparing it with the other algorithms for the traveling salesman problem in a way that's easily accessible
- As you apply different algorithms, the current best path is saved and used as input to whatever you run next. (e.g. shortest path first -> branch and bound). The order in which you apply different algorithms to the problem is sometimes referred to the meta-heuristic strategy.

### Heuristic algorithms

Heuristic algorithms attempt to find a good approximation of the optimal path within a more _reasonable_ amount of time.

**Construction** - Build a path (e.g. shortest path)

- Shortest Path
- Arbitrary Insertion
- Furthest Insertion
- Nearest Insertion
- Convex Hull Insertion\*
- Simulated Annealing\*
- MTZ Formulation

**Improvement** - Attempt to take an existing constructed path and improve on it

- 2-Opt Inversion
- 2-Opt Reciprcal Exchange\*

### Exhaustive algorithms

Exhaustive algorithms will always find possible solution by evaluating every possible path. These algorithms are typically significantly more expensive then the heuristic algorithms. The exhaustive algorithms implemented so far include:

- Random Paths
- Depth First Search (Brute Force)
- Branch and Bound (Cost)
- Branch and Bound (Cost, Intersections)\*


