# Developing a Handwritten Digit Classifier with PyTorch

A deep learning project completed as part of the **Udacity Machine Learning Fundamentals Nanodegree**.

## Project Overview

This project develops a handwritten digit classification model using **PyTorch** and the **MNIST dataset**.

The model is trained to recognize handwritten digits from 0 to 9 using a neural network and is evaluated on previously unseen images.

## Objectives

- Load and preprocess the MNIST handwritten digit dataset.
- Build a neural network using PyTorch.
- Train the model to classify handwritten digits.
- Evaluate model performance on test data.
- Save the trained model for later inference.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- MNIST dataset

## Model

The project uses a neural network implemented with PyTorch.

The training workflow includes:

1. Loading the MNIST dataset.
2. Transforming and normalizing the images.
3. Creating training and testing data loaders.
4. Defining the neural network architecture.
5. Training the model using backpropagation.
6. Evaluating the model on the test dataset.
7. Saving the trained model as `saved_model.pth`.

## Dataset

The project uses the **MNIST handwritten digit dataset**, which contains grayscale images of handwritten digits from 0 to 9.

The dataset is downloaded through the PyTorch/Torchvision workflow rather than being stored directly in this repository.

## Project Structure

```text
02-developing-a-handwritten-digit-classifier-with-pytorch/
│
├── handwritten-digit-classifier-with-pytorch.ipynb
├── requirements.txt
├── saved_model.pth
└── README.md
