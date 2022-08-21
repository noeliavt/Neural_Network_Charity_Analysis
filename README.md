# Neural_Network_Charity_Analysis

## 1. Overview of the Neural Network Charity Analysis

The purpose of this project is to use deep-learning neural networks with the TensorFlow platform to analyze and classify the success of charitable donations.

## 2. Results:

* This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively, the input data has 43 features and 25,724 samples.
* The output layer is made of a unique neuron as it is a binary classification.
* We used the activation function ReLU for the hidden layers, to speed up the training process. As our output is a binary classification, Sigmoid is used on the output layer.
* The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.
* To increase the performance of the model, we applied bucketing to the feature ASK_AMT and organized the different values by intervals.
* We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.
* We also tried a different activation function (tanh) 
* None all the steps applied before helped improve the model's performance



## 3.Summary

The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.
