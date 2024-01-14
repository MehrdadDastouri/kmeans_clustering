# K-Means Clustering on Synthetic Data

Description: "This project applies the K-Means clustering algorithm on synthetic data generated using the `make_blobs` function. The clustering results are evaluated using performance metrics such as Adjusted Rand Index (ARI) and Silhouette Score."

Features:
  - Generates synthetic data with:
      - 500 samples.
      - 2 features.
      - 3 clusters.
  - Implements K-Means clustering to partition the data into clusters.
  - Visualizes:
      - The raw data with true labels.
      - The clustered data along with centroids identified by K-Means.
  - Evaluates clustering performance using:
      - Adjusted Rand Index (ARI): Measures similarity between true labels and predicted labels.
      - Silhouette Score: Measures how well samples are clustered.
