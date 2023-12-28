# 1. Simple Object Detection in TensorFlow
This Jupyter Notebook provides a step-by-step guide on performing simple object detection using pre-trained models from TensorFlow Hub. The notebook covers the following key aspects:

1. Exploration of TensorFlow Hub for object detection models.
2. Loading a selected model into the workspace.
3. Preprocessing an image for inference.
4. Running inference on the model and inspecting the output.


# 2. TensorFlow Hub Object Detection with Jupyter Notebook

This Jupyter Notebook demonstrates how to use TensorFlow Hub to perform object detection on images using various pre-trained models. The code in this notebook is based on the TensorFlow Object Detection API and utilizes TensorFlow Hub for model loading.

1. Model Selection
2. Image Selection
3. Running Inference 

# 3. Eager Few Shot Object Detection Colab

This Jupyter notebook demonstrates fine-tuning of a RetinaNet architecture on a few examples of a novel class using TensorFlow 2.x in eager mode. The notebook is based on an official tutorial from TensorFlow with minimal revisions. 

1. Rubber Ducky Data
2. Training and Testing

# 4. Zombie Detection Notebook
This Jupyter notebook trains an object detection model to detect zombies using the Tensorflow Object Detection API.

## Contents

1. Importing necessary packages from the Tensorflow Object Detection API
2. Downloading and visualizing the training images of zombies
3. Defining the label map and metadata
4. Downloading pre-trained weights from the COCO dataset
5. Configuring the RetinaNet model architecture
6. Restoring select weights from the pre-trained model
7. Setting up training parameters and optimization
8. Defining the training loop
9. Evaluating results on test images

## Model Details
The object detection model used is RetinaNet. The model is initialized with pre-trained weights on COCO and fine-tuned for the zombie detection task.

Only the classifier layers are fine-tuned while the feature extraction layers are frozen. This allows the model to retain the general features learned on COCO while adapting the classifier for zombies.

The model is trained for 100 steps with a batch size of 5. The learning rate is set at 0.01 and SGD optimizer is used with momentum of 0.9.

## Results
The trained model achieves good performance in detecting zombies on 237 test images, with over 88% recall. The predictions on the test set are saved in results.data.

