# Classification-With-Transfer-Learning-Keras
Create and train a Convolutional Neural Network (CNN) with an existing CNN model architecture, and its pre-trained weights. We will use the MobileNet model architecture along with its weights trained on the popular ImageNet dataset. By using a model with pre-trained weights, and then training just the last layers on a new dataset, we can drastically reduce the training time required to fit the model to the new data . The pre-trained model has already learned to recognize thousands on simple and complex image features, and we are using its output as the input to the last layers that we are training.

# Implementation workflow
Import Libraries and Helper functions

Download the Pet dataset and extract relevant annotations

Add functionality to create a random batch of examples and labels

Create a new model with MobileNet v2 and a new fully connected top layer

Create a data generator function and calculate training and validation steps

Get predictions on a test batch and display the test batch along with prediction
