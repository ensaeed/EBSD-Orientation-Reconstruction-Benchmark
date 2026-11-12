# EBSD Orientation Reconstruction Benchmark

## Overview

This repository accompanies the manuscript:

**Benchmarking Classical Interpolation and Graph Neural Network Methods for Missing Orientation Reconstruction in EBSD Maps**

The study compares classical interpolation techniques with a GraphSAGE-based graph neural network for reconstructing missing crystallographic orientations in electron backscatter diffraction (EBSD) maps.

## Reconstruction Methods

The benchmark evaluates four approaches:

1. Linear interpolation
2. Four-neighbour interpolation
3. Weighted graph-based interpolation
4. GraphSAGE-based orientation reconstruction

## Experimental Evaluation

The study examines:

- Randomly masked orientations at 5%, 10%, 20%, and 40% missingness
- Symmetry-aware crystallographic disorientation
- Reconstruction errors across orientation-connected component sizes
- Local disorientation and kernel average misorientation (KAM)
- Spatially correlated missingness using clustered masks

GraphSAGE is evaluated under random missingness. The clustered-missingness experiment compares the three classical reconstruction methods.

## Datasets

The study uses publicly available EBSD datasets.

**Benchmark datasets:**

Davis, Hönnige and Martina (2022), Zenodo.

https://doi.org/10.5281/zenodo.5822710

**Independent validation datasets:**

Louw (2023), *EBSD data*, Mendeley Data.

https://doi.org/10.17632/s4twvgctdp.1

The source datasets remain available from their original repositories.

## Reproducibility

The Python notebooks and supporting scripts in this repository are intended to document the reconstruction methods and experimental evaluation.

To reproduce the study, obtain the source datasets from the links above and follow the notebook instructions.

Additional environment specifications, execution instructions, and evaluation scripts will be documented as the repository is finalised.

## Citation

If you use this code, please cite the accompanying manuscript once its publication details become available.

## License

A software license will be specified after reviewing the applicable dataset and code-sharing requirements.
