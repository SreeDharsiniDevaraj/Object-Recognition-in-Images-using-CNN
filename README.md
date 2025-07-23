# Object-Recognition-in-Images-using-CNN

## Overview

This project aims to recognize the objects of 10 different classes using their images in the CIFAR-10 dataset which is available on internet, through the Convolutional Neural Network, the Deep Learning technique primarily used for Image Processing.

## Dataset

The CIFAR-10 dataset is a widely used collection of labeled color images, primarily for training machine learning and computer vision models. The 10 different classes present in CIFAR-10 are mutually exclusive and include: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. 

## Requirements

- Google Colab
- pandas
- numpy
- matplotlib
- tensorflow
- keras

## Prediction Process

1. Start with loading the CIFAR-10 dataset in Colab
2. Import tensorflow and keras
3. Build the model as model.Sequential through Convolutional layer, Pooling layer as many times so the model gets optimized. Then add Flatten and Dense layers
4. Complie, Train and Evaluate the model
5. Visualize the training history and Make Predictions to test if the Predicted Image Classes match the Actual Classes
