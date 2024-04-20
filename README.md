# Satellite Image Data Standardization and Classification

## Overview

This project involves the standardization and classification of satellite image data. The process begins with mounting the Google Colab drive to access the dataset stored in Google Drive. The dataset comprises images categorized into four classes: Cloudy, Desert, Green Area, and Water.

## Data Standardization

An empty dataframe is created to store the image paths and corresponding labels. The dataset is organized into directories for each class, and the script iterates through these directories to compile a comprehensive list of image paths and labels. This information is then saved to a CSV file for further processing.

## Importing Libraries & Data

The project utilizes libraries such as Pandas for data manipulation, NumPy for numerical operations, and Keras for building the neural network model. The standardized data is loaded from the CSV file and displayed for verification.

## Data Splits & Augmentation

The dataset is split into training and testing sets to evaluate the model's performance. The `ImageDataGenerator` from Keras is employed to augment the training data, which includes rescaling, shear transformations, and zoom operations to introduce variability and improve the model's generalization capabilities.

## Model Architecture

The neural network model is constructed using a sequential approach with convolutional layers, max pooling, and dropout to prevent overfitting. The model aims to classify the satellite images into their respective categories accurately.

## Usage

To use this project, mount your Google Drive in a Google Colab notebook and ensure the dataset is structured as required. Run the script to standardize the data, split it into training and testing sets, and then train the model for classification.

### Happy Coading😊
