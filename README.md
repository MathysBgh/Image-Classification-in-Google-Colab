# Image Classification with CIFAR-10 in Google Colab

This project demonstrates a basic image classification model using the CIFAR-10 dataset. The model is built using TensorFlow and Keras, leveraging the Google Colab environment for training and evaluation. The goal is to create and train a neural network capable of classifying images into one of ten categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Notes](#notes)
- [License](#license)

## Introduction
In this project, you will design and train your first neural network for image classification using the CIFAR-10 dataset. The model is implemented with TensorFlow's high-level API `tf.keras` and executed in the Google Colab environment. 

## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The dataset can be accessed directly from TensorFlow Datasets.

Classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Model Architecture
The initial model is a simple neural network with three dense layers:
- **Input Layer**: Flattens the 32x32 RGB images.
- **Hidden Layers**: Three dense layers with 256, 128, and 64 neurons, respectively, all using ReLU activation.
- **Output Layer**: A dense layer with 10 neurons and a softmax activation function for classification.

Later, the model is modified to include convolutional layers for improved performance.

## Installation
To run the project, you need to have TensorFlow and TensorFlow Datasets installed. You can set up your environment by running the following commands:

```
pip install tensorflow tensorflow-datasets
```

Alternatively, you can run the project directly on Google Colab, which already has the required libraries pre-installed. Open the notebook in Colab using this link: Google Colab.

