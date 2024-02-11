# Clustering Analysis on Wine Dataset
This project performs clustering analysis on the Wine dataset using various clustering algorithms and preprocessing techniques. The Wine dataset contains attributes of different types of wine along with their class labels.

## Dataset
The Wine dataset is loaded from the UCI Machine Learning Repository. It contains 178 samples and 13 features.

## Preprocessing Techniques
Several preprocessing techniques are applied to the dataset before clustering:

No Preprocessing: The dataset is used as-is without any preprocessing.
Normalization: Min-max scaling is applied to normalize the features to a range between 0 and 1.
Standardization: Standard scaling is applied to standardize the features to have a mean of 0 and a standard deviation of 1.
PCA (Principal Component Analysis): Dimensionality reduction using PCA is performed to reduce the number of features to 2 principal components.
Normalization + PCA: Min-max scaling followed by PCA.
Standardization + PCA: Standard scaling followed by PCA.
Normalization + Standardization + PCA: Min-max scaling, standard scaling, and then PCA.

## Clustering Algorithms
Three clustering algorithms are used for clustering analysis:

KMeans: Partitioning the dataset into K clusters based on centroids.
Hierarchical: Agglomerative clustering to build a hierarchy of clusters.
MeanShift: Density-based clustering to locate and adaptively determine the number of clusters.
Evaluation Metrics
Three evaluation metrics are used to evaluate the clustering results:

Silhouette Score: Measures how similar an object is to its own cluster compared to other clusters.
Davies-Bouldin Index: Computes the average similarity between each cluster and its most similar cluster.
Calinski-Harabasz Index: Ratio of the sum of between-clusters dispersion and within-cluster dispersion.
Results
The results of the clustering analysis are stored in CSV files and visualized in PNG images for each clustering algorithm. Each CSV file contains the evaluation metrics for different preprocessing techniques, and each PNG image visualizes the evaluation metrics for each preprocessing technique.

For detailed results, please refer to the CSV files in the results directory.
