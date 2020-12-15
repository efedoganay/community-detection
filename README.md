# CommunityDetection

Steps Involved:

1. Import the data from https://moviegalaxies.com/movies/download/92/Babel

2. Repeat 10 Times:
    - Find shortest path between every pair in G, using Dijkstra's shortest path algorithm.
    - For every edge, count the number of shortest paths passing through that edge.
    - Find and remove the edge on which the maximum number of shortest paths pass.
   
Notes:

Most of the supplementary codes are taken from https://algs4.cs.princeton.edu/code/

The main implementation is in DijkstraUndirectedSP.java

Example animation:

![Alt Text](https://media.giphy.com/media/8FF7aL37fO1zX7v4iT/giphy.gif)
