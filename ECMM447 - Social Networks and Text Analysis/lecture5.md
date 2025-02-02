# Groups of nodes, clustering, homophily and assortativity, community structure

Intuition: a community is an internally connected set of nodes for 
which the internal link density is greater than the external one.

Edge betweenness: The number of shortest paths between pairs of nodes 
that run along the edge.

Girvan-Newman: we recursively remove the edge with the largest betweenness 
until no edges remain.

Louvain algorithm is very fast for modularity maximisation