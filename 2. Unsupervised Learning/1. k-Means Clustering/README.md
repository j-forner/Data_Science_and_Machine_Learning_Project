# k-Means Clustering

k-means clustering is an unsupervised machine learning technique that partitions the feature space into *k* cells based on the distance between datapoints. Associated with each cluster is what's known as a centroid, which get updated at each iteration of the algorithm (along with the data points associated with each cenrtoid) until (hopefully) convergence.

In this folder, we use gradient boosting on the [california housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html "Title") to cluster houses in California into 6 groups based on geographic location.
