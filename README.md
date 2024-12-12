#Disclaimer#
This is a project that is an implementation of what I learned so far on machine learning and deep learning

## Introduction

This notebook demonstrates how to compare a `.jpeg` image uploaded by the user to a dataset contained in a `.zip` file. The goal is to predict the class of the uploaded image and compare it with the predicted class from the dataset.

The dataset is a collection of images organized into classes, and the notebook uses a deep learning model to predict the class of the uploaded image. Then, it compares this predicted class to the dataset classes.

#Setup Instructions

To get started with this notebook:

1. Open the notebook in Google Colab

3. Ensure you have the required dependencies installed:

4. Upload the `.zip` dataset file containing the images that will be used for classification.

#Usage

 Step 1: Upload the Dataset
- The `.zip` file should contain images organized by classes (folders named after classes). 
- You can upload the `.zip` file using the file uploader in Colab.

Step 2: Upload the Image for Comparison
- Use the file uploader to upload a `.jpeg` image that you want to compare against the dataset.

Step 3: Dataset Unzipping and Preprocessing
- The notebook will unzip the dataset and preprocess the images for training or classification.
- The dataset is then split into training and validation sets.

Step 4: Model Training
- The notebook uses a Convolutional Neural Network (CNN) to train the model on the dataset.
- Once trained, the model predicts the class of the uploaded `.jpeg` image.

Step 5: Class Comparison
- The predicted class for the uploaded image is compared to the actual class in the dataset.

Key Features:
- Upload and process a `.jpeg` image.
- Unzip and use dataset from a `.zip` file.
- Predict the class of the uploaded image using a trained CNN.
- Compare the predicted class with the dataset.

### Example:
1. Upload a `.zip` dataset file:
    - Dataset consists of images categorized into folders named by their respective classes (e.g., `cloudy`, `rain`, etc.).
   
2. Upload a `.jpeg` image:
    - Upload an image for comparison.
   
3. Model Training:
    - The model classifies the uploaded image and compares it with the predicted class from the dataset.


If you’d like to contribute to this notebook:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Create a pull request.
