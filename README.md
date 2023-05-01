# Crypto Clustering

## Overview

The Crypto Clustering project uses the K-means clustering machine learning technique to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA).


## Dependencies

- Python
- pandas
- NumPy
- scikit-learn
- hvPlot


## Steps

1. Load and preprocess the data.
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.

## Conclusion

The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the relative effect of dimensionality reduction on the clustering process.
