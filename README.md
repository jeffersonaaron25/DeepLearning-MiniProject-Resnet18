# DeepLearning-MiniProject-Resnet18
This repository contains the code for a deep learning mini project based on the ResNet18 architecture. The project includes training a modified ResNet18 model on CIFAR-10 dataset and evaluating its performance on a test set. The goal of the project was to reduce the number of parameters in the ResNet18 model without sacrificing too much accuracy. This project was done by Jacob Fishman and Jefferson Aaron from NYU Tandon School of Engineering. 

# Dataset
The dataset used for this project is the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes. The dataset is divided into 50,000 training images and 10,000 testing images.

# Requirements
To run the code in this repository, you will need to have the following installed:

Python 3.6 or higher
PyTorch
NumPy
Matplotlib

# Usage
To run the code, you can use the provided Google Colaboratory notebook under 'notebooks' directory. The notebook includes step-by-step instructions on how to load the dataset, preprocess the data, train the model, and evaluate its performance. It also includes the settings that we used to achieve reduced parameters for our ResNet18 model.

# Results
Our approach resulted in a ResNet18 model with fewer parameters, while still achieving a decent accuracy on the CIFAR-10 dataset. Specifically, we were able to reduce the number of parameters from 11.2 million to 4.9 million, with a test accuracy of 89.42%.

License
This project is licensed under the terms of the MIT license.

Acknowledgments
The ResNet18 implementation was based on the PyTorch implementation provided in the torchvision package.
