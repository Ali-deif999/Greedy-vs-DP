Greedy vs. Dynamic Programming Visualization

This project demonstrates the difference between Greedy and Dynamic Programming (DP) algorithms in finding the minimum cost path across a grid (moving only Right or Down).

Algorithms Implemented

Greedy (Red): Makes the "locally optimal" choice by picking the cheapest immediate neighbor at every step.

Pros: Fast linear time complexity O(N).

Cons: Shortsighted; often fails to find the true global minimum.

Dynamic Programming (Blue): Uses Tabulation to calculate the minimum cumulative cost to reach every cell, then Backtracks from the end to the start.

Pros: Guaranteed to find the global optimal path.

Cons: Slower quadratic time complexity O(N^2).

Usage

Open project.html in any modern web browser. Click Run Comparison to see a step-by-step animation of how each algorithm makes decisions.
