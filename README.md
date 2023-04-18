# Generating Diverse and Discriminatory Knapsack Instances by Searching for Novelty in Variable Dimensions of Feature-Space

## Authors

* Alejandro Marrero: amarrerd@ull.edu.es
* Eduardo Segredo: esegredo@ull.edu.es
* Emma Hart: e.hart@napier.ac.uk
* Jakob Bossek: bossek@aim.rwth-aachen.de
* Aneta Neumann: aneta.neumann@adelaide.edu.au

## Abstract

Generating new instances via evolutionary methods is commonly used to create new benchmarking data-sets, with a focus on attempting to cover an instance-space as completely as possible. Recent approaches have exploited Quality-Diversity methods to evolve sets of instances that are both diverse and discriminatory with respect to a portfolio of solvers, but these methods can be challenging when attempting to find diversity in a high-dimensional feature-space. We address this issue by training a model based on Principal Component Analysis on existing instances to create a low-dimension projection of the high-dimension feature-vectors, and then apply Novelty Search directly in the new low-dimension space. We conduct experiments to evolve diverse and discriminatory instances of Knapsack Problems, comparing the use of Novelty Search in the original feature-space to using Novelty Search in a low-dimensional projection, and repeat over a given set of dimensions. We find that the methods are complementary: if treated as an ensemble, they collectively provide increased coverage of the space. Specifically,searching for novelty in a low-dimension space contributes 56% of the filled regions of the space, while searching directly in the feature-space covers the remaining 44%



# Relevant information

- Source code: DIGNEA, available [here]()
- $NS_f$ 8D results from PPSN are available [here](https://github.com/PAL-ULL/ns_kp_generation)