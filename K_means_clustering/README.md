# K-Means Clustering with PCA

## Overview

This project performs customer/data segmentation using the K-Means clustering algorithm. Before clustering, Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset while preserving most of the important information. PCA also helps visualize the clusters in a 2D space.

## Workflow

1. Load the dataset.
2. Scale the features using StandardScaler.
3. Apply PCA for dimensionality reduction.
4. Determine the optimal number of clusters using the Elbow Method.
5. Train the K-Means clustering model.
6. Visualize the clusters using the PCA-transformed features.

## Technologies Used

* Python
* Scikit-learn
* Seaborn

## Why PCA?

* Reduces the number of features.
* Removes redundant information.
* Improves visualization of clusters.
* Can improve clustering performance by reducing noise.

## Results

The dataset was successfully grouped into meaningful clusters using K-Means. PCA was used to project the data into two principal components, making the clusters easier to visualize and interpret.

