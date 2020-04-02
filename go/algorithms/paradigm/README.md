# Algorithms by Paradigm
An algorithmic paradigm is a generic method or approach which underlies the design of a class of algorithms. It is an abstraction higher than the notion of an algorithm, just as an algorithm is an abstraction higher than a computer program.

## Brute Force - look at all the possibilities and selects the best solution
* Linear Search
* Rain Terraces - trapping rain water problem
* Recursive Staircase - count the number of ways to reach to the top
* Maximum Subarray
* Travelling Salesman Problem - shortest possible route that visits each city and returns to the origin city
* Discrete Fourier Transform - decompose a function of time (a signal) into the frequencies that make it up

## Greedy - choose the best option at the current time, without any consideration for the future
* Jump Game
Unbound Knapsack Problem
Dijkstra Algorithm - finding shortest path to all graph vertices
* Prim’s Algorithm - finding Minimum Spanning Tree (MST) for weighted undirected graph
* Kruskal’s Algorithm - finding 
* Minimum Spanning Tree (MST) for weighted undirected graph

## Divide and Conquer - divide the problem into smaller parts and then solve those parts
* Binary Search
* Tower of Hanoi
* Pascal's Triangle
Euclidean Algorithm - calculate the Greatest Common Divisor (GCD)
* Merge Sort
* Quicksort
* Tree Depth-First Search (DFS)
* Graph Depth-First Search (DFS)
* Jump Game
* Fast Powering
* Permutations (with and without repetitions)
Combinations (with and without repetitions)

## Dynamic Programming - build up a solution using previously found sub-solutions
* Fibonacci Number
* Jump Game
* Unique Paths
* Rain Terraces - trapping rain water problem
* Recursive Staircase - count the number of ways to reach to the top
* Levenshtein Distance - minimum edit distance between two sequences
* Longest Common Subsequence (LCS)
* Longest Common Substring
* Longest Increasing Subsequence
* Shortest Common Supersequence
* 0/1 Knapsack Problem
* Integer Partition
* Maximum Subarray
* Bellman-Ford Algorithm - finding shortest path to all graph vertices
* Floyd-Warshall Algorithm - find shortest paths between all pairs of vertices
* Regular Expression Matching

## Backtracking - similarly to brute force, try to generate all possible solutions, but each time you generate next solution you test if it satisfies all conditions, and only then continue generating subsequent solutions. Otherwise, backtrack, and go on a different path of finding a solution. Normally the DFS traversal of state-space is being used.
* Jump Game
* Unique Paths
* Power Set - all subsets of a set
* Hamiltonian Cycle - Visit every vertex exactly once
* N-Queens Problem
* Knight's Tour
* Combination Sum - find all combinations that form specific sum

## Branch & Bound - remember the lowest-cost solution found at each stage of the backtracking search, and use the cost of the lowest-cost solution found so far as a lower bound on the cost of a least-cost solution to the problem, in order to discard partial solutions with costs larger than the lowest-cost solution found so far. Normally BFS traversal in combination with DFS traversal of state-space tree is being used.