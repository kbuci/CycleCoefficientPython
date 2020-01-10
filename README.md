# CycleCoefficientPython
My Implementation for computing and plotting the Cycle coefficient metric, as provided by the paper:

Janjić, Vuk and Nataša Pržulj. "The Topology of the Growing Human Interactome Data" Journal of Integrative Bioinformatics, 11.2 (2016): 27-42. Retrieved 17 Aug. 2019, from doi:10.1515/jib-2014-238

This implementation consists of initating a breadth-first search for every neighbor of a given node, expanding outwards only up to k-2 edges away, accumulating the distances between each neighbor pair.


