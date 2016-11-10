I will be working on the travelling salesman problem. The problem consists of a salesman and a set of cities. The salesman has to visit each of the cities starting from his hometown and come back to his hometown after having covered all cities in the least possible distance. The challenge is to minimize the distance covered. It is similar to the problem of finding a Hamiltonian cycle in a graph except that now we also want the cycle to be of least length among all such possible cycles. It is an NP complete problem but there are approximation algorithms/heuristic based approaches that provide a sufficiently close to accurate solution. Some of those algorithms are listed here: https://www.seas.gwu.edu/~simhaweb/champalg/tsp/tsp.html as well as in the references section of this document. 
The travelling salesman problem bears similarities to several practical applications such as laser welding done remotely in the automotive industry, designing an efficient delivery system, computational biology, X-ray crystallography and so on.

Intended tasks:
1)	Study of the following approaches to solve the problem – 
a)	K-OPT
b)	Tabu search
c)	Simulated annealing
d)	Approximate solution using Christofides heuristic
e)	The Held-Karp lower bound
f)	Lin-Kernighan algorithm, LKH-1 and LKH-2.
And few others of personal interest if I find any.
2)	Find or implement clear solutions them in C, Python, IDP and document their performance on practical data sets. Links to few websites that maintain such data sets for TSP are given below in the next section.
3)	Using the III method and make efficient implementations of the ones that can be improved. The main focus will be usage of steps Implement-reuse of knowledge gained from prior computations, and Incrementalize-usage of efficient data structures to represent the solution.
4)	Compare and document the performance of code written in part 3 to those from part 2.

Some probable sources of practical data sets:
1)	http://www.math.uwaterloo.ca/tsp/data/
2)	http://elib.zib.de/pub/mp-testdata/tsp/tsplib/tsp/
3)	https://sites.google.com/site/awazyp/tsp

