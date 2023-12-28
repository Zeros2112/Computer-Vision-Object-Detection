# 1. Transfer Learning with ResNet50 on CIFAR-10

## Overview
This Jupyter notebook demonstrates the application of transfer learning using the ResNet50 model available in Keras to train the CIFAR-10 dataset.

## Contents
1. **Imports**: Necessary libraries and modules are imported, including TensorFlow, PIL, Matplotlib, and TensorFlow Datasets.

2. **Parameters**: Batch size and class names are defined as parameters for the model.

3. **Visualization Utilities**: Functions for displaying images and plotting metrics are defined for later use.

4. **Loading and Preprocessing Data**: CIFAR-10 dataset is loaded, and preprocessing steps include normalizing images and preparing them for input into the ResNet50 model.

5. **Visualize Dataset**: Sample images from the training and validation sets are displayed using the `display_images` function.

6. **Define the Network**: The ResNet50 model is used for feature extraction, and additional layers are added for classification. The final model is compiled using Stochastic Gradient Descent as the optimizer and Sparse Categorical CrossEntropy as the loss function.

7. **Train the Model**: The model is trained on the CIFAR-10 dataset for a specified number of epochs.

8. **Evaluate the Model**: Loss and accuracy metrics are calculated using the model's `evaluate` function.

9. **Plot Loss and Accuracy Curves**: Matplotlib is used to visualize the training and validation loss as well as accuracy over epochs.

10. **Visualize Predictions**: Display a selection of images with their predicted labels to assess the model's performance.


 <br />
 <br />


# 2. Transfer Learning with Cats and Dogs Data

## Overview
This Jupyter notebook demonstrates the basic principles of transfer learning using the InceptionV3 model on a dataset containing images of cats and dogs.

## Contents
1. **Import TensorFlow**: TensorFlow and necessary modules are imported.

2. **Download and Extract Dataset**: The Cats and Dogs dataset is downloaded and extracted from the provided URL.

3. **Data Splitting**: The dataset is split into training and testing sets for both cats and dogs.

4. **Data Augmentation**: The `ImageDataGenerator` is used for data augmentation, providing a more varied training set for improved model generalization.

5. **Model Creation**: InceptionV3 is used as the base model with pre-trained weights. Additional layers are added for fine-tuning on cats and dogs data.

6. **Training the Model**: The model is compiled and trained on the augmented dataset.

7. **Visualizing Training and Validation Accuracy**: Matplotlib is used to plot the training and validation accuracy over epochs.

8. **Prediction on Test Image**: The user is prompted to upload an image, and the model predicts whether it's a cat or a dog.


 <br />
 <br />

 # 3. Predicting Bounding Bird Boxes 

## Overview 
This Jupyter Notebook is designed for predicting bounding boxes around birds in images using transfer learning with MobileNet V2 on the Caltech Birds - 2010 dataset. 

## Contents 
1. **Set up your Colab Environment**

2. **Set up Data Location**: Add a shortcut to the dataset folder ("TF3 C3 W1 Data") to your Google Drive.

3. **Choose GPU Runtime**: 

4. **Mount Your Drive**: 

5. **Imports**: 

6. **Load and Visualize Data**: 

7. **Define and Train the Model**: 

8. **Validate the Model**:

9. **Save the Model**

10. **Visualize Predictions**








