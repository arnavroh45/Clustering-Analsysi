# Clustering-Analsysis

## Dataset Used - Iris

## Preprocessing Techniques:
1) No Preprocessing: The raw data is used directly for clustering.
2) Normalization: The data is scaled to have values between 0 and 1.
3) PCA (Principal Component Analysis): Dimensionality reduction technique is applied to the data to reduce its dimensionality.
4) Transform + Normalization: First, PCA is applied for dimensionality reduction, followed by normalization.
5) Transform + Normalization + PCA: PCA is applied, then normalization, and finally PCA again for further dimensionality reduction.

## Evaluation Parameters
1) Silhouette Score: The silhouette score measures how similar an object is to its own cluster compared to other clusters. A high silhouette score indicates that the object is well matched to its own cluster and poorly matched to neighboring clusters.
2) Calinski-Harabasz Score: The Calinski-Harabasz score is the ratio of the between-cluster dispersion mean and the within-cluster dispersion. It measures the ratio of between-cluster distance to within-cluster distance. A higher Calinski-Harabasz score indicates better-defined clusters.
3) Davies-Bouldin Score: The Davies-Bouldin score is the average similarity measure of each cluster with its most similar cluster, where similarity is the ratio of within-cluster distances to between-cluster distances. Lower Davies-Bouldin score indicates better clustering. 


## Conclusion:
The PCA preprocessing technique performs better in terms of Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score, suggesting more well-defined and separated clusters compared to other preprocessing techniques.
