# DFS (Depth-First Search)

<!------------------------------------------------------------------------------------------------------------------------------------->

Depth-first search (DFS) at its core is simply a traversal algorithm that attempts to traverse as "deep" as possible before backtracking.
You can run this algorithm on many different data structures, but this page will talk about DFS for graphs, as described in [CLRS](https://kidpiano.github.io/Algorithms/CLRS.html){:target="_blank"}.

(insert example, disconnected graph, order nodes starting from 1)

Note that in this DFS algorithm, all nodes will be traversed even if there are more than one disconnected components.

During a depth-first search, we can also keep track of additional information:
1. The state (color) of a node:
    * White = undiscovered
    * Gray = discovered, but not finished
    * Black = finished (finished traversing every branch along this node)
 2. The discover and finish time of each node
 3. The parent of each node during the traversal (we can use this to generate the DFS predecessor subgraph, which will be a forest)
 4. The classification of each edge in the predecessor subgraph
     * Tree edge:
     * Back edge: 
     * Forward edge:
     * Cross edge:

edge classification asdfasdf

Why would we want to keep track of this additional information?
There are many reasons why, some of which we will answer later. For now, here is an example of DFS on the same graph, but with this additional information:

(insert DFS example)

Below is pseudocode for DFS, and an example implementation in Java:

(insert code snippets)

<!------------------------------------------------------------------------------------------------------------------------------------->

## Detecting cycles 

One asdfasdfadf

<!------------------------------------------------------------------------------------------------------------------------------------->

## Topological Sorting

<!------------------------------------------------------------------------------------------------------------------------------------->

## Finding Strongly Connected Components

<!------------------------------------------------------------------------------------------------------------------------------------->

