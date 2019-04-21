# Clustering-Methods-Comparison
This repository is to demonstrate the descriptions and difference between clustering methods. 

**Descriptions of Clustering Methods**
- **K-means clustering technique** 
 finds the k numbers of centroids. It measures the euclidean distances between observations and centroids and assigns them to the corresponding groups based on the shortest euclidean distance. This process will reiterte several times till the centroids are fixed. The key difference of Kmeans clustering is it could find k clusters.

- **Agglomerative clustering** 
 defines each observation as a cluster in the beginning. Then clusters are merged together into new different clusters based on the similarity based on the minimizing linkage criteria, which measures the similarity. What differentiates this clustering technique is it doesn't require a specified k and with a tree model.

- **Gaussian mixture model** 
 is a category of probabilistic model which states that all generated data points are derived from a mixture of a finite Gaussian distributions that has no known parameters. This algorithm could use its ability to identify non-flat geometry or uneven cluster sizes.

- **DBSCAN clustering** 
 separates the data according to its density. What makes this algorithm different is that it's capable of clustering non-flat geometry and uneven cluster sizes. However, when handling data with high dimensionality, the distance threshold would be hard to estimate.

- **Spectral clustering technique** 
 starts the following steps :(1)Create a similarity graph between our N objects to cluster.(2)Compute the first k eigenvectors of its Laplacian matrix to define a feature vector for each object.(3)Run k-means on these features to separate objects into k classes. However, spectral clustering is computationally expensive unless the graph is sparse and the similarity matrix can be efficiently constructed.
