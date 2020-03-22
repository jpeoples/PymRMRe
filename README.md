# PymRMRe

## Description
Feature selection is one of the main challenges in analyzing high-throughput genomic data. Minimum redundancy maximum relevance (mRMR) is a particularly fast feature selection method for finding a set of both relevant and complementary features. The Pymrmre package, extend the mRMR technique by using an ensemble approach to better explore the feature space and build more robust predictors. To deal with the computational complexity of the ensemble approach, the main functions of the package are implemented and parallelized in C++ using openMP Application Programming Interface. The package also supports making best selections with some fixed-selected features.

## Prerequisite
`
Python(>=3.6.0)
`
<br>
`
Cython(>=0.29.12)
`
<br>
`
numpy(>=1.16.4)
`
<br>
`
pandas(>=0.25.0)
`


## Installation
