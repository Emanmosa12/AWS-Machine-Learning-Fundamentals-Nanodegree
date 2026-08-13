# Landmark Classification and Tagging for Social Media

A deep learning project completed as part of the **AWS Machine Learning Fundamentals Nanodegree**.

## Project Overview

This project develops an image classification system that can recognize landmarks in images and support automatic tagging of social media content.

The project explores two approaches to landmark classification:

1. Building a Convolutional Neural Network (CNN) from scratch.
2. Using transfer learning with a pretrained image classification model.

The project also includes an application notebook demonstrating how the trained model can be used to make predictions on new images.

## Objectives

The main objectives of the project are to:

- Prepare and process landmark image data.
- Build and train a CNN from scratch.
- Evaluate the performance of the CNN.
- Apply transfer learning using a pretrained model.
- Compare different approaches for landmark classification.
- Use the trained model to predict landmarks in new images.
- Develop a foundation for automatically tagging landmark images on social media.

## Project Components

### 1. CNN from Scratch

The first approach builds a convolutional neural network from the ground up using PyTorch.

The workflow includes:

- Loading and preprocessing image data.
- Creating training, validation, and test datasets.
- Defining a CNN architecture.
- Training the model with PyTorch.
- Evaluating classification performance.

The implementation is documented in:

`cnn_from_scratch.ipynb`

### 2. Transfer Learning

The second approach uses a pretrained image classification model and adapts it to the landmark classification task.

Transfer learning allows the model to take advantage of visual features learned from a large existing dataset, which can improve performance and reduce the amount of training required.

The implementation is documented in:

`transfer_learning.ipynb`

### 3. Landmark Prediction Application

The project also includes an application workflow for using the trained model to predict the landmark shown in a new image.

The prediction workflow is demonstrated in:

`app.ipynb`

## Project Structure

```text
03-landmark-classification-and-tagging-for-social-media/
│
├── src/
│   ├── train.py
│   ├── transfer.py
│   ├── data.py
│   ├── predictor.py
│   ├── optimization.py
│   ├── create_submit_pkg.py
│   ├── model.py
│   ├── helpers.py
│   └── __init__.py
│
├── cnn_from_scratch.ipynb
├── transfer_learning.ipynb
├── app.ipynb
└── README.md
