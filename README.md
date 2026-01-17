# Stanford-Cars-Image-Classification-Deep-Learning-

🚗 Stanford Cars Image Classification (Deep Learning)
📌 Overview

This project focuses on fine-grained image classification using the Stanford Cars Dataset, which contains images of 196 different car models. The objective is to build a deep learning model that can accurately classify a car image into its correct category.

Fine-grained classification is challenging because many classes are visually similar, requiring the model to learn subtle differences in shape, design, and structure.

📂 Dataset

Stanford Cars Dataset includes:

16,185 images of cars

196 classes (car makes and models)

Split into:

8,144 training images

8,041 testing images


🧠 Problem Statement

Given an image of a car, the goal is to predict the correct car model from 196 possible categories using deep learning techniques.

🏗️ Approach
🔹 Data Preprocessing:

Image resizing to a fixed dimension (e.g., 224×224)

Normalization using ImageNet mean and standard deviation

Data augmentation:

Random rotation

Horizontal flip

Random cropping

🔹 Model Used:

Transfer learning with a pre-trained convolutional neural network:

Model: ResNet-50 (or you can replace with your model if different)

Pre-trained on: ImageNet

Fine-tuned on: Stanford Cars dataset

🔹 Training Details:

Loss Function: Cross-Entropy Loss

Optimizer: Adam

Learning Rate: 0.0001

📊 Results
Metric	Value
Training Accuracy	~92%
Validation Accuracy	~88%
Test Accuracy	~86%

Batch Size: 32

Epochs: 20 (modify as per your training)
