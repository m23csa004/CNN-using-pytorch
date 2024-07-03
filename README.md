CNN Network using PyTorch

This repository contains an implementation of a Convolutional Neural Network (CNN) using PyTorch to classify images from the MNIST dataset. The implementation includes two experiments:

1.Basic classification using the original MNIST dataset with 10 classes.
2.Modified classification by combining the original 10 classes into 4 new classes.

Experiment 1

In the first experiment, a CNN is trained on the original MNIST dataset to classify handwritten digits into 10 classes (0-9).

Model Architecture

3 Convolutional Layers with ReLU activations and MaxPooling
1 Fully Connected Layer

Training
Optimizer: Adam
Loss Function: CrossEntropyLoss
Number of Epochs: 10

Experiment 2

In the second experiment, the original 10 classes are combined into 4 new classes based on a specified mapping:

Class 0: 0, 6
Class 1: 1, 7
Class 2: 2, 3, 5, 8
Class 3: 4, 9

Model Architecture
The architecture remains the same as in Experiment 1.

Training
Same optimizer,loss fn.,no. of epoch  as experiment 1.

Results

The training and test accuracy for both experiments are plotted. Confusion matrices are also generated to evaluate the performance of the models.