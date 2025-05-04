# CMPS 2200 Recitation 09

## Answers

**Name:** Charlie Coun
**Name:** Vincent Camacho


Place all written answers from `recitation-09.md` here for easier grading.



- **2)** The algorithm runs Prim's algorithm once per component, and since each run of Prim's Algorithm has a work of O(logV) for each heap operation, with the number of heap operations being O(E), so putting all components together would give a total worst-case work of O((V+E)logV).

  
- **4)** The algorithm computes the euclidean distance between every pair of cities, and since there are $O(n^{2})$ pairs, the work for this step would be $O(n^{2})$. Then it runs Prim's algorithm on a graph of $O(n^{2})$ edges, where each edge may result in a heap operation which takes O(logn) work. Combining all these steps gives a total work of $O(n^{2}logn)$
