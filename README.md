# TNSDC-Generative-AI-Project-au211521104051

# Traffic Sign Configuration

## Overview
Traffic sign configuration using Convolutional Neural Networks (CNNs) involves training neural networks on labeled datasets of traffic sign images to classify and recognize different signs. CNNs utilize convolutional layers to automatically learn hierarchical features from input images, enabling robust recognition of signs despite variations in lighting, weather, and background.

## Setup
To get started, follow these steps:

1.Clone this repository to your local machine.

2.Install the necessary dependency.

## Installation
1. ### NumPy:
    NumPy is used for numerical computing and is essential for handling arrays and matrices efficiently.

2. ### Matplotlib:
   Matplotlib is a plotting library used for visualizing data.

3. ### OpenCV (cv2):
   OpenCV is a library mainly aimed at real-time computer vision. You need it for image processing tasks.

4. ### scikit-learn:
   Scikit-learn provides simple and efficient tools for data mining and data analysis. You're using it here for splitting the dataset.

5. ### TensorFlow:
   TensorFlow is a powerful deep learning framework developed by Google. You're using it for building and training the CNN model.

## Dataset
The dataset for the code provided in your question is synthetic. This means that the images of traffic signs are generated programmatically within the code rather than being sourced from an external dataset. The function generate_traffic_signs() creates synthetic images of traffic signs by drawing them on blank images and adding noise to simulate variations.

Here's a brief overview of how the dataset is generated within the code:

1. The function generate_traffic_signs() creates synthetic images of traffic signs for three classes: 'stop', 'speed_limit_30', and 'speed_limit_60'.

2. For each class, a specified number of images (num_images_per_class) is generated.

3. A blank image is created, and the corresponding traffic sign class is drawn on the image using OpenCV's cv2.putText() function.

4. Noise is added to the image to simulate variations using NumPy's random functions.

5. The generated image and its corresponding label (class index) are appended to the dataset.

# Usage 
The code provided generates synthetic traffic sign images, trains a convolutional neural network (CNN) model to classify these images, and plots the training history.

# Results
The result of the provided code is a trained convolutional neural network (CNN) model for classifying synthetic traffic sign images, along with a plot showing the training history of the model's accuracy.

# Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.



   
