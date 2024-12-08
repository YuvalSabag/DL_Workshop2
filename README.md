## **Human Activity Recognition Using Wearable Sensors**

This project focuses on advancing **Human Activity Recognition (HAR)** using **time-series data** collected from wearable sensors. The primary objective is to classify human activities (e.g., walking, running, sitting) by leveraging both classical machine learning techniques and advanced deep learning models.By integrating feature extraction, self-supervised learning, and neural network enhancements, this project offers effective solutions for time-series classification.

The dataset comprises both labeled and unlabeled acceleration data, providing a robust benchmark for evaluating various machine learning and deep learning approaches. Key tasks include data preprocessing, model training, performance evaluation, and experimentation with state-of-the-art techniques such as **1D-CNNs**, **autoencoders**, and **bidirectional LSTMs**.


### **Key Objectives**
1. **Data Analysis and Preprocessing**:
   - Conduct exploratory analysis to understand dataset structure and activity distribution.
   - Normalize sensor data and segment it into fixed-length windows.
   - Extract statistical features (e.g., mean, variance) for classical models.

2. **Self-Supervised Learning**:
   - Pretrain models with tasks like **Masked Autoencoders** and **Next Step Prediction** to leverage unlabeled data.

3. **Model Development**:
   - Train classical models (**Random Forest**, **XGBoost**) as baselines.
   - Develop **1D-CNNs** and **LSTMs** for temporal pattern recognition.
   - Enhance architectures with **bidirectional LSTMs**, dropout, and batch normalization.

4. **Performance Evaluation**:
   - Use metrics like **accuracy**, **precision**, and **loss** for evaluation.
   - Compare classical models and deep learning architectures to assess strengths and limitations.
  

### **Dataset Analysis**
- The dataset comprises time-series acceleration data from wearable sensors.
- Includes both labeled and unlabeled data for supervised and self-supervised tasks.
- Key preprocessing steps include:
  - Segmentation of time-series data into smaller, fixed-length windows.
  - Sensor normalization to handle variability in measurements.

### **Methodology**
1. **Classical Models**:
   - Feature extraction (e.g., mean, variance, skewness) to represent time-series data.
   - Training using **Random Forest** and **XGBoost** with hyperparameter tuning.

2. **Deep Learning Models**:
   - **1D Convolutional Neural Networks (1D-CNNs)**:
     - Designed to capture local temporal patterns.
     - Enhanced using dropout and batch normalization.
   - **Long Short-Term Memory Networks (LSTMs)**:
     - Capture sequential dependencies in time-series data.
     - Improved with bidirectional layers for better context understanding.
   - **Autoencoders**:
     - Used for pretraining and feature extraction in self-supervised tasks.

3. **Evaluation**:
   - Metrics: Accuracy, precision, recall, and loss.
   - Visualization: Confusion matrices, learning curves, and feature importance analysis.
