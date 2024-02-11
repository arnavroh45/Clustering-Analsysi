# Clustering-Analsysis

Dataset Used - Iris

Preprocessing Techniques:
No Preprocessing: The raw data is used directly for clustering.
Normalization: The data is scaled to have values between 0 and 1.
PCA (Principal Component Analysis): Dimensionality reduction technique is applied to the data to reduce its dimensionality.
Transform + Normalization: First, PCA is applied for dimensionality reduction, followed by normalization.
Transform + Normalization + PCA: PCA is applied, then normalization, and finally PCA again for further dimensionality reduction.

Conclusion:
PCA seems to slightly improve the clustering performance in terms of silhouette score and Davies-Bouldin score compared to no preprocessing. This indicates that scaling the features can enhance the clustering quality.
PCA reduces the dimensionality of the data but doesn't significantly improve clustering performance in this case. It may be due to the nature of the Iris dataset, which doesn't have a high dimensionality to start with.
Transform + Normalization performs the best among all techniques. It suggests that applying PCA for dimensionality reduction followed by normalization can lead to better clustering results.
Transform + Normalization + PCA doesn't show a significant improvement over the Transform + Normalization technique. It might be because performing PCA twice doesn't add much value in this scenario.
