# Reflection

During this challenge, I implemented the K-Means clustering algorithm entirely from scratch without relying on Scikit-learn. This required manually handling centroid initialization, Euclidean distance calculations, iterative cluster assignments, and centroid updates until convergence.

The implementation deepened my understanding of unsupervised learning and highlighted the impact of centroid initialization on clustering quality. I also gained experience in preprocessing data, visualizing clustered results, and analyzing algorithmic time complexity.

One challenge was ensuring convergence without creating empty clusters. This was addressed by retaining the previous centroid whenever a cluster became empty.

Future improvements include implementing K-Means++, the Elbow Method for selecting the optimal number of clusters, and support for higher-dimensional datasets.
