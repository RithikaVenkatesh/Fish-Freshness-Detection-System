# Fish-Freshness-Detection-System
AquaFresh AI: Automated Fish Freshness Detection System

## Overview:

The Fish Freshness Detection System is an AI-powered web application developed to automatically determine whether a fish is fresh or spoiled using image classification. The project leverages Transfer Learning with MobileNetV2 to analyze images and provide accurate predictions in real time.

## Problem Statement:

Determining fish freshness manually requires expertise and is often subjective. Traditional methods rely on visual inspection, smell, and touch, which may not always produce consistent results.

This project addresses the problem by using Artificial Intelligence and Computer Vision to automatically classify fish images as Fresh or Spoiled, helping improve food quality and reduce waste.

## Model Architecture:

The project uses MobileNetV2, a lightweight Convolutional Neural Network (CNN) pre-trained on the ImageNet dataset.

Transfer Learning was applied by replacing the final classification layer and training the model on a custom fish freshness dataset.

### The workflow includes:

Image Collection
Image Preprocessing
Data Augmentation
Model Training
Validation
Prediction
Web Deployment


## Technologies Used:
* Python
* TensorFlow / Keras
* OpenCV
* HTML
* CSS
* JavaScript

## Features:
* Upload fish image
* Predict Fresh or Spoiled
* MobileNetV2 Transfer Learning
* Web Interface

## Dataset:

The model was trained using a dataset containing images of Fresh and Spoiled fish.

The dataset includes multiple fish images collected for binary image classification.

Note: The dataset has not been uploaded to this repository due to its large size.

## Screenshot:

1. OUTPUT PAGE
<img width="1170" height="515" alt="image" src="https://github.com/user-attachments/assets/27a9a4ee-8e68-4afc-b8a5-23ef6e17f00f" />


2. FRESH
<img width="1375" height="1144" alt="image" src="https://github.com/user-attachments/assets/f89da2b7-f888-422f-9da5-0013779a8c47" />

3. SPOILED
<img width="1170" height="515" alt="image" src="https://github.com/user-attachments/assets/b0940789-3445-4801-a6e6-8cbf4e885846" />


