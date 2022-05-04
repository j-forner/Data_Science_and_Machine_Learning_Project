# Deep Neural Networks

Deep neural networks extend our previous notion of a single neuron model to one that includes multiple layers, each of which has a variable number of nodes. The network learns patterns for classification purposes as follows: first we feed in training data to our network in what's called the "feedforward" phase; then, we compute the predictive performance of the model during training with the use of a loss function (in our case the mean-squared error loss function); lastly, based on the performance of the model, information is "backpropagated" to adjust the models' weights and biases, in the form of stochastic gradient descent. After performing these steps on all of the training data, the model has "learned" and we proceed by testing the it on data it hasn't seen.

In this folder, we train our model on the [fashion_mnist dataset](https://keras.io/api/datasets/fashion_mnist/ "Title"). This dataset includes 60,000 testing images of clothing items that fit into 10 different categories, and 10,000 training images of clothing items. The labels for the items are as follows:

0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle Boot