# Social-Network-Analytics-Community-Detection

In Social Network Analysis (SNA), community structure is an important feature of complex network. There are many researches on detecting community or cluster in graph with the objective to understand functional properties and community structures. Community detection early researches require global knowledge of network, which is not realistic to most real world network. Due to the increase of online social network, the new challenges are to develop methods to support community detection based on local information-only and network modularity. This paper present state of the art of methods in community detection research and propose the direction of future community detection research.


## The Girvan-Newman Algorithm 
For the detection and analysis of community structure relies on the iterative elimination of edges that have the highest number of shortest paths between nodes passing through them. By removing edges from the graph one-by-one, the network breaks down into smaller pieces, so-called communities. The algorithm was introduced by Michelle Girvan and Mark Newman.

## The Girvan-Newman algorithm can be divided into four main steps:

## 1.
For every edge in a graph, calculate the edge betweenness centrality.
## 2.
Remove the edge with the highest betweenness centrality.
## 3.
Calculate the betweenness centrality for every remaining edge.
## 4.
Repeat steps 2-4 until there are no more edges left.
