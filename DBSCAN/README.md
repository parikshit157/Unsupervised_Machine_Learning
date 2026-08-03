# Clustering Algorithms: K-Means and DBSCAN

## Overview

This project demonstrates the application of K-Means and DBSCAN clustering algorithms on different datasets. K-Means and DBSCAN are applied to the Make Moons dataset to compare their performance on non-linear data, while DBSCAN is also applied to the Iris dataset to analyze density-based clustering on a real-world dataset.

## Workflow

1. Generate the Make Moons dataset and Iris
2. Apply K-Means clustering on the Make Moons dataset.
3. Apply DBSCAN clustering on the Make Moons dataset.
4. Compare the clustering results using visualizations.
5. Load the Iris dataset.
6. Apply DBSCAN clustering on the Iris dataset.
7. Visualize and analyze the clustering results.

## Technologies Used

* Python
* Scikit-learn
* Seaborn

## Results

* On the **Make Moons** dataset, K-Means struggles to identify the non-linear cluster structure, whereas DBSCAN successfully detects the natural moon-shaped clusters.
* On the **Iris** dataset, DBSCAN groups samples based on data density and can identify noise points without requiring the number of clusters in advance.

