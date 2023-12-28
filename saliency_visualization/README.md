# 1. Class Activation Maps with Fashion MNIST

This repository demonstrates the implementation of Class Activation Maps (CAM) on a model trained with the Fashion MNIST dataset using Keras.

## Overview

In this lab, you will learn how to generate Class Activation Maps, which highlight the regions of an image that contribute the most to the model's prediction. The notebook covers the following key steps:

1. **Building the Classifier**: Creating a simple convolutional neural network using the Keras Sequential API.

2. **Training the Model**: Compiling and training the model on the Fashion MNIST dataset.

3. **Generating Class Activation Maps**: Implementing CAM by extracting features from the last convolutional layer and visualizing the important regions of an image.

<br />

# 2. Saliency Maps Assignment

## Overview

This repository contains the code for the "Saliency Maps" assignment as part of the course. The goal of this assignment is to generate saliency maps for images using a Cats vs. Dogs classifier.

## Files

- `C3W4_Assignment.ipynb`: Jupyter notebook with the main code for the assignment.
- `images.zip`: Zip file containing the normalized tensor images generated during the assignment.

## Instructions

1. **Environment Setup**: Ensure you have the necessary environment set up to run the code in the Jupyter notebook.

2. **Dataset**: The code uses the Cats vs. Dogs dataset from TensorFlow Datasets. Make sure the required images (`cat1.jpg`, `cat2.jpg`, `catanddog.jpg`, `dog1.jpg`, `dog2.jpg`) are available.

3. **Initial Weights**: The code loads untrained weights (`0_epochs.h5`) and pre-trained weights (`15_epochs.h5`). Ensure these weight files are present in the directory.

4. **Training the Model**: The model is trained for 3 epochs. You can train further after submitting for grading.

5. **Generate Saliency Maps**: Saliency maps are generated for different epochs (`0`, `15`, and optionally `95`). The resulting images are stored in the `images.zip` file.

6. **Additional Weights (Optional)**: If you want to visualize saliency maps at `95` epochs, download the additional weights file (`95_epochs.h5`) and run the corresponding code.

## Viewing Saliency Maps

To view the saliency maps, download and extract the `images.zip` file. The normalized tensor images for different epochs will be available.
