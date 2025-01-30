# Clustering Techniques on the Iris Dataset

## Objective

This project focuses on applying clustering techniques to the **Iris dataset** to evaluate different unsupervised learning approaches.

## Dataset

The **Iris dataset**, available in the `sklearn` library, consists of numerical features representing different species of flowers. Since clustering is an unsupervised task, the `species` column is excluded from the analysis.

## Implementation Details

### Loading and Preprocessing

- The dataset is loaded using `sklearn.datasets.load_iris()`.
- The target column, representing species labels, is dropped to ensure an unsupervised learning approach.

## Clustering Algorithms

### KMeans Clustering

KMeans clustering partitions data into **K clusters** by:
1. Initializing centroids.
2. Assigning points to the nearest centroid.
3. Iteratively updating centroids until convergence.

Given the Iris dataset’s well-separated groups, KMeans is an effective choice for clustering.

- Applied **KMeans clustering** to the preprocessed dataset.
- Visualized the clusters using **scatter plots**.

### Hierarchical Clustering

Hierarchical clustering builds a nested cluster hierarchy using:
- **Agglomerative clustering** (bottom-up).
- **Divisive clustering** (top-down).

It does not require specifying the number of clusters beforehand, making it suitable for exploring the natural structure of the dataset.

- Implemented **Agglomerative Clustering**.
- Generated a **dendrogram** for hierarchical visualization.
- Visualized clusters with **scatter plots**.

## Submission

- The project is provided as a **Jupyter Notebook (`.ipynb`)** and is available in this repository.
- Explanations, code, and visualizations are included to facilitate understanding.

## Author

- **Musthahina P**
- **30/01/2025:** [Add the Submission Date]

---

