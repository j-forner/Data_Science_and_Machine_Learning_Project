# Random forests

Random forests is an ensemble learning method that aggregates the predictions of multiple decision trees to solve classification or regression tasks. For classification tasks, random forests output the class selected by most trees, whereas for regression tasks, they output the mean prediction of the individual trees is [https://en.wikipedia.org/wiki/Random_forest].

In this folder, we employ a random forest to predict whether a penguin is of the Gentoo or Chinstrap species, similar to the task we solved using bagging. We again use the [penguins dataset](https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv "Title"), and focus specifically on the bill length and bill depth features.