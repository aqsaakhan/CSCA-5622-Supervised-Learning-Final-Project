# Ensemble Learning for Multi-Class ECG Heartbeat Categorization - Supervised Learning Project
#### Aqsa Anwar
#### 27th-Aug-2024
**[GitHub Repository](https://github.com/aqsaakhan/CSCA-5622-Supervised-Learning-Final-Project)**

## 1. Introduction
This project serves as the final project for my **['Introduction to Machine Learning: Supervised Learning'](https://github.com/aqsaakhan/CSCA-5622-Supervised-Learning-Final-Project/blob/main/Final%20Project.ipynb)** course. In this project I aim to develop a model that could potentially assist in the early detection of cardiac abnormalities, contributing to more efficient and accurate cardiac health monitoring. An ECG (Electrocardiogram) is a medical test that measures the electrical signals of the heart and is essential for diagnosing many heart related diseases. A healthy individual's heartbeat on an ECG is characterized by a distinctive waveform, representing the normal functioning of the heart.

However, when the heart is not functioning optimally, the ECG detects distortions to the anticipated waveform, and severe and life-threatening arrhythmias might present a different or nonexistent waveform altogether.
### 1.1 Dataset Overview
The **[ECG Heartbeat Categorization Dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat)**  is a comprehensive collection of electrocardiogram (ECG) signals, designed for the classification of heartbeats. This dataset is derived from two renowned sources in the field of heartbeat classification:

MIT-BIH Arrhythmia Dataset:

- Contains 109,446 samples
- Categorized into 5 classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]
- Sampling frequency: 125Hz


The PTB Diagnostic ECG Database:

- Contains 14,552 samples
- Categorized into 2 classes (normal and abnormal)
- Sampling frequency: 125Hz

All samples in the dataset have been preprocessed: they are cropped, downsampled, and padded with zeros to a fixed dimension of 188 data points. This preprocessing ensures uniformity across all samples.
The dataset is split into four CSV files:

- mitbih_train.csv
- mitbih_test.csv
- ptbdb_abnormal.csv
- ptbdb_normal.csv

Each row in these CSV files represents a single heartbeat, with the last column indicating the class label.

### 1.2 Project Objectives
The main objectives of this project are:

- **Data Exploration (EDA):** To gain in-depth insights into the ECG signal patterns across different heartbeat categories.
- **Data Cleaning, Data Preprocessing and Feature Engineering:** To prepare the data for machine learning models, including handling any data quality issues and creating relevant features.
- **Model Development:** We'll develop various models including Logistic Regression, Random Forest, XGBoost, and Ensemble Model(Random Forest and XGBoost)
- **Hyperparameter Tuning:** We'll also hypertune our best performing model to further optimze it's perfomance.
- **SMOTE Analysis:** We'll also perform SMOTE analysis combined with our ensemble method.
- **Model Evaluation and Comparison:** To assess the performance of different models in classifying heartbeats and identify the most effective approach.
- **Practical Application:** To develop a model that could potentially assist in the early detection of cardiac abnormalities, contributing to more efficient and accurate cardiac health monitoring.
