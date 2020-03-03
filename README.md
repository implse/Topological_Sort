# Topological Sort

The topological sort algorithm takes a directed acyclic (DAG) graph and returns a list of nodes where each node appears before all the nodes it point to.

### Depth First Search for Topological Sort

The algorithm loop through each node of the graph, in an arbitrary order, initiating a depth first search that terminates when it hits any node that has already been visited since the beginning or the node has no outgoing edges.

Time Complexity : `O (V + E)`

The algorithm is simply DFS with an extra stack.

### Applications

- Build Systems.
- Advanced Packaging Tool.
- Task Scheduling.
- Pre-requisite or dependencies problem.



<p align="center">
  <img width="480" height="360" src="images\Topological_Sort.png">
</p>


<p align="center">
  <img width="800" height="120" src="images\Topological_Sort_Result.png">
</p>
