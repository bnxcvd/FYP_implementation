# FYP_implementation

## Input Explanation:

The first line contains two numbers, the number of items $n$ and the number of agents $m$.

Next is an $m*n$ matrix which is the utility function. The entry in $i$-th row and $j$ column is $u_i(j)$

The last $m$ lines describe the relationship network. Line $i$ starts with a number $Adj_i$, which is the number of $F_i$'s neighbors. The following numbers are those neighbors. Suppose $j$ is one of them, then an edge exists from $F_i$ to $F_j$.

## Example:

```
4 4               //4 items and 4 agents
0.2 0.2 0.2 0.4   //utility function
0.2 0.2 0.2 0.4
0.2 0.2 0.2 0.4
0.2 0.2 0.2 0.4
1 1               //F_0 has one neighbor, F_1, meaning that F_0->F_1
1 2
1 0
1 0
```
