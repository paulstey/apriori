# Christian Borgelt's _a-priori_ Algorithm

## Description

Apriori is a program to find association rules and frequent item sets (also closed and maximal as well as generators) with the Apriori algorithm [Agrawal and Srikant 1994], which carries out a breadth first search on the subset lattice and determines the support of item sets by subset tests. This implementation is pretty fast as it uses a prefix tree to organize the counters for the item sets. However, Apriori is outperformed on basically all data sets by depth-first algorithms like Eclat or FP-growth.

This program is currently useful only, because it can generate association rules directly (while all other programs available on this web site find only frequent item sets) and allows to evaluate association rules as well as item sets by a large range of different measures.
