## **Human Activity Recognition Using Wearable Sensors**

This project focuses on advancing **Human Activity Recognition (HAR)** using **time-series data** collected from wearable sensors. The primary objective is to classify human activities (e.g., walking, running, sitting) into **18 distinct categories** by leveraging both classical machine learning techniques and advanced deep learning models. By integrating feature extraction, self-supervised learning, and neural network enhancements, this project demonstrates effective solutions for time-series classification.

The dataset comprises both labeled and unlabeled acceleration data, offering a robust benchmark for evaluating various machine learning and deep learning approaches. Key tasks include data preprocessing, model training, performance evaluation, and experimentation with state-of-the-art techniques such as **1D-CNNs**, **autoencoders**, and **bidirectional LSTMs**.

&nbsp;  
### **Key Objectives**
1. **Data Analysis and Preprocessing**:
   - Conduct exploratory analysis to understand the dataset structure and activity distribution.
   - Normalize sensor data and segment it into fixed-length windows.
   - Extract statistical features (e.g., mean, variance) to support classical models.

2. **Self-Supervised Learning**:
   - Pretrain models using tasks like **Masked Autoencoders** and **Next Step Prediction** to leverage unlabeled data.

3. **Model Development**:
   - Train classical machine learning models (**Random Forest**, **XGBoost**) as baselines.
   - Develop **1D-CNNs** and **LSTMs** to capture temporal patterns in the data.
   - Enhance architectures with **bidirectional LSTMs**, dropout regularization, and batch normalization.

4. **Performance Evaluation**:
   - Use metrics such as **accuracy**, **precision**, and **loss** to evaluate models.
   - Compare the performance of classical models and deep learning architectures to identify strengths and limitations.
     
&nbsp;  
### **Dataset Analysis**
- **Data Source**: Time-series acceleration data collected from wearable sensors.
- **Classes**: 18 distinct human activities for classification.
- **Data Composition**:
  - Includes both labeled and unlabeled data for supervised and self-supervised tasks.
- **Preprocessing**:
  - Segment time-series data into fixed-length windows.
  - Normalize sensor readings to ensure consistency across measurements.

&nbsp;  
### **Methodology**
#### **1. Classical Models**:
   - Extract statistical features (e.g., mean, variance, skewness) from time-series data.
   - Train models such as **Random Forest** and **XGBoost**, including hyperparameter tuning for optimization.

#### **2. Deep Learning Models**:
   - **1D Convolutional Neural Networks (1D-CNNs)**:
     - Capture local temporal patterns in time-series data.
     - Enhanced with dropout and batch normalization for regularization.
   - **Long Short-Term Memory Networks (LSTMs)**:
     - Model sequential dependencies in time-series data.
     - Improved with bidirectional layers for better context representation.
   - **Autoencoders**:
     - Used for pretraining and extracting features in self-supervised learning tasks.

#### **3. Evaluation**:
   - Assess models using metrics like **accuracy**, **precision**, **recall**, and **loss**.
   - Visualize results with confusion matrices, learning curves, and feature importance analysis.
