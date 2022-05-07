# k-Nearest Neighbors

k-Nearest Neighbors is an algorithm used for both classification and regression tasks that assumes that like data are spatially close to one another. When classifying or regressing on a particular piece of data using this algorithm, we start by finding the *k* data points closest to it with respect to a chosen metric. Then we either take the plurality among their classes or the average of their values, respectively, and assign this value to the data point of interest.

In this folder, we use the bill length and bill depth feature measurements from the [penguins dataset](https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv "Title") to classify between Gentoo and Chinstrap penguin species.