# Quantum-Computing
Solving Boolean SAT Problem Using Grover's Problem

About Grover's Algorithm : Grover's algorithm, which takes O(N1/2) time, is the fastest possible quantum algorithm for searching an unsorted database. It provides "only" a quadratic speedup, unlike other quantum algorithms, which can provide exponential speedup over their classical counterparts.

Implementation : 

Grover search is a quantum algorithm that can be used to search for solutions to unstructured problems quadratically faster than its classical counterparts. Now, we are going to use the Grover's algorithm to solve a particular combinatorial Boolean satisfiability problem.

Now the Boolean satisfiability problem is the problem of determining if there exists an interpretation that satisfies a given Boolean formula. In other words, it asks whether the variables of a given Boolean formula can be consistently replaced by the values TRUE or FALSE in such a way that the formula evaluates to TRUE. If this is the case, the formula is called satisfiable. On the other hand, if no such assignment exists, the function expressed by the formula is FALSE for all possible variable assignments and the formula is unsatisfiable. This can be seen as a search problem, where the solution is the assignment where the Boolean formula is satisfied.

referances/resoursces:

https://www.quantiki.org/wiki/grovers-search-algorithm
