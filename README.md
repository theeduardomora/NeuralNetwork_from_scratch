# NeuralNetwork_from_scratch

MLP Neural Network built in Python without using tensorflow or any ML library, just numpy and standard Python library. 

I wanted to build a neural network from scratch in Python. I made some progress before I stumbled across this video (https://www.youtube.com/watch?v=w8yWXqWQYmU&t=123s) and its accompanying notebook (https://www.kaggle.com/wwsalmon/simple-mnist-nn-from-scratch-numpy-no-tf-keras) which elegantly covered everything that I wanted to do.

This code is largely a duplicate of the code mentioned above, except that He initialization is used instead of uniform random initialization for the weights along with  a hidden layer of 128 nodes instead of 10 nodes. This network attains an accuracy of 91% on both training and testing data for the  MNIST dataset. 
