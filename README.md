# Deep-Learning-Customer-Churn-Prediction-Using-ANN

## Bank Customer Churn Prediction Using ANN 🏦📉

## 📌 Overview
This repository contains an end-to-end Machine Learning pipeline that predicts whether a bank customer is likely to churn (leave the bank) using an Artificial Neural Network (ANN). The project covers the entire lifecycle, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and an inference pipeline for real-time predictions.

## 🛠️ Technical Stack & Tools
The project is built utilizing the following technologies:
* **Core Languages:** Python
* **Deep Learning Framework:** TensorFlow & Keras (v2.20.0)
* **Data Manipulation & Math:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Data Visualization:** Matplotlib, TensorBoard
* **Deployment/UI (Planned/Included):** Streamlit

## 📂 Project Structure
```text
├── Churn_Modelling.csv      # Raw dataset
├── EDA.ipynb                # Data preprocessing, feature engineering, and model training
├── Prediction.ipynb         # Inference script for making predictions on new data
├── requirements.txt         # Dependencies and library versions
├── model.h5                 # Saved ANN model
├── scaler                   # Pickle file for StandardScaler
├── labelEncoder             # Pickle file for Gender LabelEncoder
└── ohEncoder                # Pickle file for Geography OneHotEncoder

## 🚀 Features
### Robust Data Preprocessing:
Includes automated dropping of irrelevant columns, Label Encoding for binary categories, and One-Hot Encoding for multi-class categories.

### Artificial Neural Network:
A highly optimized Sequential model featuring dense layers with ReLU activation to prevent vanishing gradients, and a Sigmoid output layer for binary classification.

### Advanced Training Callbacks:
Utilizes EarlyStopping to prevent overfitting by monitoring validation loss, and TensorBoard for tracking training metrics across epochs.

### Seamless Inference:
A dedicated prediction pipeline that ingests raw customer data dictionaries, transforms them using the pre-fitted encoders/scalers, and outputs a clear churn probability.
