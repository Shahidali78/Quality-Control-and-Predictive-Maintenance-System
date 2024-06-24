
## Intelligent Quality Control and Predictive Maintenance System
#### Overview
This project aims to enhance manufacturing processes using machine learning and deep learning techniques for defect detection and predictive maintenance. The project utilizes the MVTec AD dataset for defect detection and the SECOM dataset for predictive maintenance.

### Introduction
Quality control and predictive maintenance are crucial in manufacturing. Traditional methods are manual and inefficient. This project automates these processes, improving efficiency and reducing costs.

### Objectives
##### Defect Detection
Build a CNN model using the MVTec AD dataset to detect defects.
##### 
Predictive Maintenance
Develop a Random Forest model using the SECOM dataset to predict equipment failures.
Datasets
MVTec Anomaly Detection (AD) Dataset
High-resolution images for various defect types.
Used for training and testing the defect detection model.
SECOM Manufacturing Dataset
Sensor data indicating pass/fail status.
Used for developing the predictive maintenance model.
Methodology
Defect Detection
Data Preprocessing: Resize images, apply data augmentation, and normalize.
Model: CNN with convolutional, max-pooling, and fully connected layers.
Training: Adam optimizer with categorical crossentropy loss. Early stopping and model checkpointing used.
Predictive Maintenance
Data Preprocessing: Handle missing values, scale features, and split dataset.
Model: Random Forest classifier with hyperparameter tuning using GridSearchCV.
Training: Optimize model parameters through cross-validation.
