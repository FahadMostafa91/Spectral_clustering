# Spectral_clustering
Spectral clustering refers to a family of algorithms that cluster eigenvectors derived from the matrix that represents the input data’s graph. An important step in this method is running the kernel function that is applied on the input data to generate a NXN similarity matrix or graph (where N is our number of input observations). Subsequent steps include computing the normalised graph Laplacian from this similarity matrix, getting the eigensystem of this graph, and lastly applying k-means on the top K eigenvectors to get the K clusters. Clustering in this way adds flexibility in the range of data that may be analyzed and spectral clustering will often outperform k-means.
