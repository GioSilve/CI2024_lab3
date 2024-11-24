# CI2024_lab3

## Algorithms used
- Iterative deepening A*

## Description
The chosen path search algorithm for the solution of this problem is the Iterative deepening A*, since we found it to be a good algorithm for this kind of problem, and in order to implement it we started from the pseudo code provided in the corresponding [Wikipedia page](https://en.wikipedia.org/wiki/Iterative_deepening_A*)
and added some optimizations to further improve the performance. As heuristics we chose the Manhattan distance heuristics, as we found it to be the most commonly used for this problem. The solution ended up working well with random 3x3 matrices, but unfortunately could not provide the results we hoped for when we 
tried to increase the dimensions of the matrix, since it often wouldn't be able to solve the problem in a reasonable amount of time.

## Collaboration
Ideas and suggestions were shared with fellow [colleague](https://github.com/mickp18)
