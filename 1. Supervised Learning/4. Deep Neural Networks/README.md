# Deep Neural Networks

Deep neural networks extend our previous notion of a single neuron model to one that includes multiple layers, each of which has a variable number of nodes. The network learns patterns for classification problems as follows: first we feed in training data to our network in what's called the "feedforward" phase; then, we compute the predictive performance of the model during training with the use of a loss function (in our case the mean-squared error loss function); lastly, based on the performance of the model, information is "backpropagated" to adjust the models' weights and biases - note that in our case this is done in the form of stochastic gradient descent. After performing these steps on all of the training data, the model has "learned" and we proceed by testing it on data it hasn't seen.

In this folder, we use the popular [fashion_mnist dataset](https://keras.io/api/datasets/fashion_mnist/ "Title"). This dataset includes 70,000 images of clothing items that are divided in the following way: 60,000 training images (for training our deep neural network), and 10,000 test images (for testing our model). There are 10 classes for these fashion articles, which are as follows:

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