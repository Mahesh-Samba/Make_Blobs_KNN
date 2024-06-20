This project uses synthetic data generated with `make_blobs` to simulate a dataset with 300 samples spread across 4 clusters. 
Initially, the data distribution is visualized through a scatter plot. 
After applying KMeans clustering with 4 clusters, the data is re-plotted to show cluster assignments and centroids.
Basic statistics such as data shape, min/max values, mean, and standard deviation are computed to understand the dataset. Finally, the model's performance is evaluated using the inertia metric, 
providing insight into how well KMeans partitions the data into distinct clusters based on feature similarities.
