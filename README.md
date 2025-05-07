# AEDS II Practical Work  
**Traveling Salesman Problem (TSP) Solutions Analysis**  

## Part 1: Brute-Force Approach *(Lucas)*  

### Objectives:  
1. **Brute-Force Algorithm Implementation**  
   - Develop an exhaustive search algorithm that evaluates **all possible routes** and selects the optimal (shortest) path.  
   - *Note:* Any graph representation (adjacency matrix/list) is acceptable.  

2. **Instance Generation & Testing**  
   - Automatically generate random TSP instances with city sizes ranging from **2 to n**.  
   - Focus on measurable sizes (e.g., **10–14 cities** due to computational constraints).  

3. **Performance Analysis**  
   - Record and compare **execution times** for each instance.  
   - Document scalability challenges (e.g., exponential time complexity).  

---

## Part 2: Heuristic Approach *(Emanuel)*  

### Objectives:  
1. **Heuristic Implementation**  
   - Implement a heuristic (e.g., **Nearest Neighbor**, 2-opt, or Christofides) to approximate TSP solutions efficiently.  

2. **Benchmarking on Real-World Instances**  
   - Test the heuristic on three provided datasets:  
     - **si535.tsp**: 535 cities (upper diagonal adjacency matrix).  
     - **pa561.tsp**: 561 cities (lower diagonal adjacency matrix).  
     - **si1032.tsp**: 1032 cities (upper diagonal adjacency matrix).  

3. **Solution Validation**  
   - Calculate and verify the total distance of the heuristic-derived route.  
   - Compare results with known optima (if available) or baseline heuristics.  

---
