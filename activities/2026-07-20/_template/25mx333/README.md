# K-Means Clustering from Scratch

## Introduction
This project focuses on implementing the K-Means Clustering algorithm using Python without the Scikit-learn library. The goal is to divide customer location data into multiple groups based on similarity and distance.

## Problem Statement
Given a set of 2D customer coordinates, the algorithm groups the data into K distinct zones by repeatedly updating cluster centroids until the results become stable.

## Approach
The solution follows these steps:

1. Import the customer dataset containing X and Y coordinates.
2. Choose the number of clusters (K).
3. Select initial centroids from the dataset.
4. Compute the Euclidean distance between each point and the centroids.
5. Assign every point to the closest centroid.
6. Calculate new centroid positions by taking the average of all points in each cluster.
7. Repeat the process until there is no significant change in centroid values.

## System Workflow
Dataset → Initialize Centroids → Calculate Distances → Create Clusters → Update Centroids → Check Convergence → Final Output

## Model Evaluation
The algorithm was evaluated by checking:
- Stability of centroid positions.
- Visual separation of clusters.
- Number of iterations required for convergence.
- Correct assignment of data points to clusters.

## Time Complexity
- Distance calculation: O(n × k)
- Centroid update: O(n)
- Total complexity: O(t × n × k)

Where:
- n = number of data points
- k = number of clusters
- t = number of iterations

## Space Complexity
- O(n + k), where n is the number of data points and k is the number of centroids.

## Tools and Technologies
- Python
- NumPy
- Matplotlib

## Results
The implementation successfully grouped customer data into meaningful clusters and generated final centroid coordinates. The visualization made it easier to understand the distribution of customer zones.

## Future Improvements
- Add automatic selection of the optimal K value using the Elbow Method.
- Support larger datasets.
- Create an interactive dashboard for visualization.
- Extend the solution to higher-dimensional data.
