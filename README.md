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

## Results:
# Faculty faces detection:
<img width="1710" height="1074" alt="Number of faces detected" src="https://github.com/user-attachments/assets/62123533-c9fc-4f00-9542-d33032844d34" />

# Faculty faces faces plotted in Hue–Saturation space
<img width="1110" height="544" alt="Screenshot 2026-02-15 at 4 51 29 PM" src="https://github.com/user-attachments/assets/954b1ed5-3783-47d5-9df0-7d45ec99ff15" />

# Clusters with centroids (Faculty)
<img width="1121" height="560" alt="Screenshot 2026-02-15 at 4 51 44 PM" src="https://github.com/user-attachments/assets/bf084feb-3424-4764-a359-0673de56e615" />

# Shahi Tharoor face detecting
<img width="396" height="425" alt="Detected face" src="https://github.com/user-attachments/assets/dabd38f6-1f1b-4ff7-866a-03745f543ff4" />

# Faculty faces & Shahi tharoor faces plotted in Hue–Saturation space
<img width="1118" height="560" alt="Screenshot 2026-02-15 at 4 51 55 PM" src="https://github.com/user-attachments/assets/6abb70eb-3810-450f-8ddf-79f9b18f9612" />

## Clusters with centroids (Faculty & Shahi Tharoor)
<img width="1111" height="562" alt="Screenshot 2026-02-15 at 4 52 01 PM" src="https://github.com/user-attachments/assets/3ef7212e-653b-490c-a063-2d090f477a0c" />


