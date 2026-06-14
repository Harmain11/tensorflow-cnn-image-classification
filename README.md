# TensorFlow CNN Image Classification

## Overview
This notebook demonstrates building and training a convolutional neural network (CNN) using TensorFlow and Keras for image classification. It covers data preprocessing with `ImageDataGenerator`, constructing the CNN architecture, training the model on image data organized in class-specific directories, and saving the trained model.

## Features
- Data preprocessing with image rescaling and directory-based batch loading.
- CNN architecture with multiple convolutional and max pooling layers.
- Model training with categorical crossentropy loss for multi-class classification.
- Saving the trained model for future inference or fine-tuning.

## Tech Stack
- Python  
- Jupyter Notebook / Google Colab  
- TensorFlow  
- Keras  
- ImageDataGenerator from Keras for image augmentation and preprocessing

## How to Use
1. Organize your image dataset in a root `data` folder with subfolders named by class and containing corresponding images.  
2. Open the notebook in Google Colab or Jupyter Notebook.  
3. Run all cells to preprocess the data, build and train the CNN model.  
4. The trained model will be saved as `classification.h5` in the working directory.

## Status
This notebook is well-organized and prepared for presentation in a GitHub repository.