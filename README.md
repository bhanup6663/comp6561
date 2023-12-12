# Ford-Fulkerson Maximum Flow Algorithm Simulation

## Overview

This Python code implements a simulation of the Ford-Fulkerson algorithm for finding the maximum flow in a network. The simulation includes the utilization of various augmenting path algorithms to enhance the performance of the Ford-Fulkerson algorithm. These augmenting path algorithms include:

- Shortest Augmenting Path (SAP)
- Depth-First Search (DFS)
- Maximum Capacity (MaxCap)
- Random Augmenting Path (Random)

This project allows to compare the performance and behavior of these different augmenting path algorithms in the context of solving maximum flow problems in networks.

## Usage

To run the simulation, follow these steps:

1. Run code using following command

   ```bash
   python ff3.py
   ```
Sample output
```commandline
_______________________________________________________________

Simulation for n=150, r=0.2, upperCap=100
------------

Algorithm: SAP
Total Edges in the Graph: 1223
Paths: 45
Mean Length: 11.0
Mean Proportional Length: 1.0
Elapsed Time: 0.0180 seconds
------------

Algorithm: dfs_like
Total Edges in the Graph: 1223
Paths: 45
Mean Length: 80.24444444444444
Mean Proportional Length: 1.0
Elapsed Time: 0.0129 seconds
------------

Algorithm: MaxCap
Total Edges in the Graph: 1223
Paths: 45
Mean Length: 14.28888888888889
Mean Proportional Length: 1.0
Elapsed Time: 0.0236 seconds
------------

Algorithm: Randon_Dij
Total Edges in the Graph: 1223
Paths: 45
Mean Length: 15.244444444444444
Mean Proportional Length: 1.0
Elapsed Time: 0.0260 seconds

```
