# K-Nearest Neighbors Algorithm for Cluster Analysis

This project implements the K-Nearest Neighbors (KNN) algorithm for cluster analysis, focusing on grouping data based on proximity to centroids. The objective is to identify natural clusters within complex data structures.

## Dataset Overview

The dataset comprises two sets of synthetic data generated using `make_moons` and `make_circles` from Scikit-learn. These datasets represent challenging clustering scenarios with distinct shapes:

- `make_moons`: Generates two interleaving half circles (moons).
- `make_circles`: Produces a large circle containing a smaller circle in 2D.

The two datasets are combined and visualized to demonstrate the KNN algorithm's ability to handle complex clustering tasks.

### Data Source

The dataset is created using the following Scikit-learn functions:
- `sklearn.datasets.make_moons`
- `sklearn.datasets.make_circles`

## KNN Algorithm

The KNN algorithm, a versatile method for classification, regression, and clustering, is applied here for identifying clusters in the combined dataset of moons and circles.

### Implementation

Implemented in Python, the project leverages NumPy for numerical operations and Matplotlib for visualizing the complex data structure and clustering results.

## Visualization and Analysis

The project includes visualizations that compare the original data distribution to the KNN-assigned clusters. The effectiveness of the KNN algorithm in clustering non-linear and intricately shaped data is a key focus of this analysis.

## Conclusion and Further Steps

This project illustrates the KNN algorithm's application in clustering non-linear data structures. Future work might explore algorithm optimizations for various data shapes and the inclusion of more robust clustering evaluation metrics.

---

For implementation details and results, please refer to the Jupyter notebook included in this repository.
