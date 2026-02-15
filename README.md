# Lab-5-Distance-based-Classification
Implementing face detection with using distance based classification. It also analyzes KNN classification, focusing on cross-validation and the bias-variance tradeoff to optimize results.

## Overview

This project demonstrates face detection, feature extraction, and clustering using computer vision and machine learning techniques.

Faces were detected from a group image, features were extracted using HSV color space, and clustering was performed using k-Means. A template face image was also classified based on the trained clustering model.

## Aim

The objectives of this lab were:
Detect faces in an image using OpenCV
Extract meaningful features (Hue and Saturation)
Cluster faces using k-Means
Classify a new template face
Visualize clustering results

## Methodology
# Step 1: Face Detection

Faces were detected using:
Haar Cascade Classifier
OpenCV
Bounding boxes were drawn around each detected face.

# Step 2: Feature Extraction

Each detected face was:
Converted to HSV color space
Mean Hue and Saturation values were extracted
These values were used as feature vectors

# Step 3: Clustering

k-Means clustering was applied
Faces were grouped based on similarity
Centroids were computed and plotted

# Step 4: Template Image Classification

A template face image was:
Face detected
Features extracted
Cluster predicted using trained model

## Key Findings

Hue and Saturation features can effectively group similar faces.
k-Means clustering successfully separated faces into clusters.
The template image was correctly classified into one of the clusters.
Visualization helps interpret clustering results clearly.

## Tools and Libraries Used

Python
NumPy
Matplotlib
Scikit-learn
CLustering
