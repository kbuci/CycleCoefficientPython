# CycleCoefficientPython
My Implementation for computing and plotting the Cycle coefficient metric, from the paper "The Topology of the Growing Human Interactome Data" (Janji, Przulj) metric (and my WIP of a parallel approach).

A cycle coefficient for node v and length k for a given graph, Ck(v), is the proportion of pairs of neighbors of v being connected by a path with length at most k-2, where the path does not go through v. The average of these k value cycle coefficients across all nodes yields the probability that two nodes with a common neighbor share a path at most k - 2 in length.

Janjić, Vuk and Nataša Pržulj. "The Topology of the Growing Human Interactome Data" Journal of Integrative Bioinformatics, 11.2 (2016): 27-42. Retrieved 17 Aug. 2019, from doi:10.1515/jib-2014-238

This implementation consists of initating a breadth-first search for every neighbor of a given node, expanding outwards only up to k-2 edges away, accumulating the distances between each neighbor pair.


