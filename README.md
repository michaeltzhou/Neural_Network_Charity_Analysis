# Neural_Network_Charity_Analysis

## Overview
The purpose of this challenge is to take the provided dataset to create a binary classifier of whether organizations that recieve funding from Alphabet Soup will be successful using machine learning and neural networks.

## Results
### Data Preprocessing
The ["IS_SUCCESSFUL"] column is considered the target for the model. ["EIN"] and ["NAME"] are not considered features nor targets so they were removed during preprocessing. The other columns would be considered features, with a greater emphasis on ["CLASSIFICATION"] and ["APPLICATION_TYPE"].

### Compiling, Training, and Evaluating the Model
The hidden layer activation was set to "sigmoid" and "relu" and the output later activation was set to "linear". The first layer had 80 nodes and the second layer had 30 nodes. Target model performance was unable to be achieved, but modifying the model to add neurons to hidden layers, adding additional hidden layers, removing noise, and changing the activation function of hidden layers could be modified to try and increase the score. This was not done due to runtime contraints, but could be done in the future.
