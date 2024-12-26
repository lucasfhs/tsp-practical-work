# AedsII Practical Work

## Part 1 (Lucas)

1. Implement the **brute force method** to solve the problem, i.e., an algorithm that determines all possible routes and selects the best (shortest) one.
2. Generate instances with sizes from 2 to n and apply the method implemented in item 1.
3. Compute the execution time while applying the brute force method on each of the generated instances. The method should be applied to as many instances as possible (likely with sizes ranging from 10 to 14 cities).

**Note:** The instances should be automatically generated with random weights. Any type of graph representation can be used.

---

## Part 2 (Emanuel)

1. Implement a **heuristic** to find a solution to the Traveling Salesman Problem. The choice of heuristic is up to you.
2. Apply the implemented method from the previous item to three problem instances available on Moodle:
   - **si535.tsp**: The problem has 535 cities, and the distances are available in the form of an adjacency matrix, but only the upper diagonal of this matrix.
   - **pa561.tsp**: The problem has 561 cities, and the distances are available in the form of an adjacency matrix, but only the lower diagonal of this matrix.
   - **si1032.tsp**: The problem has 1032 cities, and the distances are available in the form of an adjacency matrix, but only the upper diagonal of this matrix.
3. Verify the distance calculated by your heuristic.
