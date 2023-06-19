# VRP Solver using PSO
This project is an implementation of a solution to the vehicle routing problem (VRP) using particle swarm optimization (PSO) algorithm. The VRP is a combinatorial optimization problem that involves finding the optimal route for a fleet of vehicles to service a set of customers, subject to capacity and distance constraints.

# Background
The VRP is a well-known and complex optimization problem that has applications in various fields, including transportation, logistics, and supply chain management. The problem involves finding the optimal routes for a fleet of vehicles to service a set of customers, while minimizing the total travel time or distance traveled, and respecting capacity constraints. The VRP is an NP-hard problem, which means that finding the optimal solution is computationally expensive and time-consuming.

Particle swarm optimization (PSO) is a metaheuristic optimization algorithm that is inspired by the social behavior of bird flocking or fish schooling. The algorithm optimizes a problem by iteratively trying to improve a candidate solution with regard to a given measure of quality. In each iteration, the PSO algorithm updates the position and velocity of each particle in the swarm based on the best solutions found so far by the swarm and by the particle itself.

# Implementation
The VRP solver using PSO was implemented in Python programming language. The implementation uses the PySwarm library for the PSO algorithm and the Google Maps API for distance calculations. The solver takes as input a set of customers, with their locations, demands, and time windows, as well as the number of vehicles and their capacity. The solver outputs the optimal routes for the vehicles to service the customers, with the total distance traveled and the total time required.
