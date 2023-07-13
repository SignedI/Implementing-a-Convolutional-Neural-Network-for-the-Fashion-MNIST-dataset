# Implementing-a-Convolutional-Neural-Network-for-the-Fashion-MNIST-dataset

In this project, I try to implement a Convolutional Neural Network, and train it, so that it can tell the fashion item which is being displayed in the image. 

The Fashion MNIST dataset was used for this purpose. It consistes of 60,000 training images and 10,000 testing images, each of which is a 28X28 pixel grayscale image with a label of its type added to it. 

In this model, we first reshape the training dataset according to the channel size, which we have kept 1. After that, we form the Convolutional Neural Network model using tensorflow and keras, and then train it using the given dataset. The output that we get is the accuracy score with which it was able to predict the test images.
