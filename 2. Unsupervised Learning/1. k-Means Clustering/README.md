# *k*-Means Clustering

*k*-means clustering is an unsupervised machine learning technique that partitions the feature space into *k* cells based on the distance between datapoints and what are known as centroids, described [in this article](https://en.wikipedia.org/wiki/K-means_clustering "Title"). The centroid and the its associated datapoints get updated at each iteration of the algorithm until (hopefully) convergence is reached.

In this folder, we use gradient boosting on the [california housing dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices "Title") to cluster houses in California into 6 groups based on geographic location. The data attributes are as follows:

1. longitude: A measure of how far west a house is; a higher value is farther west
2. latitude: A measure of how far north a house is; a higher value is farther north
3. housingMedianAge: Median age of a house within a block; a lower number is a newer building
4. totalRooms: Total number of rooms within a block
5. totalBedrooms: Total number of bedrooms within a block
6. population: Total number of people residing within a block
7. households: Total number of households, a group of people residing within a home unit, for a block
8. medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. medianHouseValue: Median house value for households within a block (measured in US Dollars)
10. oceanProximity: Location of the house w.r.t ocean/sea

The above descriptions are also taken from the [california housing dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices "Title").
