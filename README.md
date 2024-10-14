This project addresses the multi-type vaccine distribution problem, where vaccines must be delivered from a central hub to multiple nodes (locations). The goal is to minimize the total travel distance while ensuring delivery constraints are met. Two approaches are implemented:

Exact Optimization using Gurobi:

Finds the optimal route considering multiple constraints like time windows, cooling requirements, fuel limits, and vaccine demand.
Greedy Heuristic:

Provides a faster, suboptimal solution by always selecting the nearest node, which is useful for quick approximations in large-scale problems.
