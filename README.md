# Heuristic_Search

This repository involve implementing heuristic functions and solving problems using search algorithms. Ensure the heuristic functions are admissible (never overestimate the cost to reach the goal).

8-Puzzle Problem with Breadth-First Search (BFS)

Implement a heuristic function for the 8-puzzle problem (3x3 grid with tiles numbered 1–8 and one blank tile). Use Manhattan distance as the heuristic to estimate the cost to the goal state (tiles in order 1–8 with the blank at the bottom-right). Solve the puzzle using Breadth-First Search to find the optimal solution. Input: Initial state (e.g., [[1, 2, 3], [4, 0, 5], [7, 8, 6]], where 0 is the blank tile). Output: Sequence of moves (up, down, left, right) to reach the goal state. Requirement: Display the initial state, heuristic values for explored states, and the optimal solution path.

Block Arrangement Problem with Hill Climbing

Implement a heuristic function for a block arrangement problem with four blocks labeled A, B, C, and D, arranged in a linear stack. The goal is to arrange the blocks in the order [A, B, C, D] from top to bottom. Use a heuristic that counts the number of blocks out of place compared to the goal state. Solve the problem using the Hill Climbing algorithm. Input: Initial stack (e.g., [C, A, D, B]). Output: Sequence of moves (swap two adjacent blocks) to reach the goal state. Requirement: Display the initial stack, heuristic values for each state, and the solution path (or indicate if the algorithm gets stuck).
