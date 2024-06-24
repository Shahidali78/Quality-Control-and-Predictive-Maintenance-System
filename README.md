Intelligent Quality Control and Predictive Maintenance System
Overview
This project aims to enhance manufacturing processes by implementing intelligent quality control and predictive maintenance systems using machine learning and deep learning techniques. The project leverages the MVTec AD dataset for defect detection and the SECOM dataset for predictive maintenance, providing robust solutions to identify product defects and predict potential equipment failures.

Table of Contents
Introduction
Objectives
Datasets
Methodology
Setup and Installation
Usage
Results
Conclusion
References
Introduction
In the manufacturing industry, quality control and predictive maintenance are crucial for ensuring product reliability and operational efficiency. Traditional methods are often manual and time-consuming, leading to inefficiencies and increased costs. This project aims to automate and enhance these processes using advanced machine learning models.

Objectives
The primary objectives of this project are:

Defect Detection Using CNNs: Build a Convolutional Neural Network (CNN) model to detect various types of defects in products using the MVTec Anomaly Detection (AD) dataset.
Predictive Maintenance Using Random Forests: Develop a predictive maintenance model using the SECOM manufacturing dataset to predict equipment failures.
Datasets
MVTec Anomaly Detection (AD) Dataset
Description: High-resolution images for various defect types across different object categories.
Application: Used for training and testing the defect detection model.
SECOM Manufacturing Dataset
Description: Sensor data collected from a semiconductor manufacturing process, indicating pass/fail status.
Application: Used for developing the predictive maintenance model.
Methodology
Defect Detection
Data Preprocessing: Resize images, apply data augmentation (rotation, width shift, height shift, horizontal flip), and normalize.
Model: Convolutional Neural Network (CNN) with convolutional layers, max-pooling layers, and fully connected layers, ending with a softmax activation function.
Training: Use Adam optimizer with categorical crossentropy as the loss function, implementing early stopping and model checkpointing.
Predictive Maintenance
Data Preprocessing: Handle missing values, perform feature scaling, and split the dataset into training and testing sets.
Model: Random Forest classifier with hyperparameter tuning using GridSearchCV.
