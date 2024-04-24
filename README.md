# Intermediate Neural Network in TensorFlow

This repository contains code for an intermediate-level neural network implemented in TensorFlow. The neural network architecture used here is a shallow neural network designed for classifying handwritten digits from the MNIST dataset.

## Dependencies

Before running the code, ensure that you have TensorFlow installed. You can view all the TensorFlow-related libraries installed on your system using the following command:

```bash
!pip freeze | grep tensorflow
```

## Setup

To specify a specific version of TensorFlow, you can install it using pip. For example:

```bash
!pip install tensorflow==2.0.0-beta0
```

Additionally, ensure that the type of runtime is set to GPU for optimal performance.

## Dataset

This neural network utilizes the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits from 0 to 9. The dataset is commonly used for training various image classification models.

## Neural Network Architecture

The architecture of the neural network used in this project is as follows:

- **Input**: 28x28 = 784 pixels
- **Hidden Layer**: 64 sigmoid neurons
- **Output Layer**: 10 softmax neurons (corresponding to the 10 possible classes)

## Loading Dependencies

The necessary dependencies are loaded using TensorFlow, including the MNIST dataset and other required modules for building and training the neural network.

## Data Loading and Preprocessing

The MNIST dataset is loaded into memory, consisting of both training and testing sets. The images are reshaped into a format suitable for feeding into the neural network, and pixel values are normalized to have a range between 0 and 1.

## Example Images

A subset of the training dataset is visualized to provide a glimpse of the handwritten digits included in the MNIST dataset.

## Usage

The code provided in this repository can be run in a Jupyter Notebook or any Python environment with TensorFlow installed. Simply execute the code cells in sequence to train and evaluate the neural network on the MNIST dataset.

