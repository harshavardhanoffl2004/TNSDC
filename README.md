# TNSDC-Generative-AI-Project-au211521104051

# Traffic Sign Configuration

## Overview
Traffic sign configuration using Convolutional Neural Networks (CNNs) involves training neural networks on labeled datasets of traffic sign images to classify and recognize different signs. CNNs utilize convolutional layers to automatically learn hierarchical features from input images, enabling robust recognition of signs despite variations in lighting, weather, and background.

## Setup
To get started, follow these steps:

1.Clone this repository to your local machine.

2.Install the necessary dependency.

# Process
## Data Generation:

•Synthetic images of traffic signs are generated using OpenCV and NumPy.

•Each image represents a traffic sign with variations added using random noise.
## Dataset Splitting:

•The generated dataset is split into training and testing sets using scikit-learn's train_test_split.

•80% of the data is allocated for training and 20% for testing.

## Data Preprocessing:

•Pixel values of images are normalized to the range [0, 1] for better convergence during training.

## Model Definition:

•A Convolutional Neural Network (CNN) model is defined using TensorFlow's Keras API.

•It consists of convolutional layers for feature extraction, max-pooling layers for downsampling, and dense layers for classification.

## Model Compilation:

•The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss function.

•Accuracy is chosen as the metric for model evaluation.

## Model Training:

•The compiled model is trained on the training data.

•Training is performed for 10 epochs with a batch size of 32.

•Validation data are used to monitor the model's performance during training.

## Training Visualization:

•Matplotlib is used to plot the training and validation accuracy over epochs.

•This allows visualization of the model's training progress and performance on unseen data.

