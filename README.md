# Human Activity Recognition Using Deep Learning

## 📌 Project Overview
This project focuses on **Human Activity Recognition (HAR)** using Machine Learning and Deep Learning techniques. The objective is to classify different human activities such as walking, sitting, standing, and laying using smartphone sensor data collected from accelerometer and gyroscope sensors.

The project uses the **UCI Human Activity Recognition Dataset** and compares multiple Machine Learning algorithms with an Artificial Neural Network (ANN).

---

# 🚀 Features
- Human activity classification using sensor data
- Comparison of ML and DL models
- Data preprocessing and feature scaling
- ANN model implementation using TensorFlow/Keras
- Confusion matrix visualization
- Performance evaluation using classification metrics

---

# 🧠 Activities Classified
The model classifies the following activities:

1. Walking
2. Walking Upstairs
3. Walking Downstairs
4. Sitting
5. Standing
6. Laying

---

# 📂 Dataset
Dataset Used: **UCI Human Activity Recognition Dataset**

The dataset contains:
- Accelerometer sensor data
- Gyroscope sensor data
- 561 extracted features
- Data collected from 30 participants

### Dataset Shape
| Dataset | Shape |
|----------|--------|
| X_train | 7352 × 561 |
| X_test | 2947 × 561 |

---

# 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

# 🤖 Models Used

## 1. Logistic Regression
Used as a baseline classification model.

## 2. Support Vector Machine (SVM)
Used for high-dimensional feature classification.

## 3. Random Forest Classifier
Ensemble learning model using multiple decision trees.

## 4. Artificial Neural Network (ANN)
Deep Learning model used for activity classification.

### ANN Architecture
- Input Layer → 561 features
- Dense Layer → 128 neurons (ReLU)
- Dropout Layer → 0.3
- Dense Layer → 64 neurons (ReLU)
- Output Layer → 6 neurons (Softmax)

---

# ⚙️ Project Workflow

## Step 1: Data Loading
- Loaded train and test datasets using Pandas.

## Step 2: Data Preprocessing
- Label encoding
- Feature scaling using StandardScaler
- Data normalization

## Step 3: Model Training
- Trained ML and DL models on processed data.

## Step 4: Model Evaluation
Models evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

## Step 5: Visualization
- Confusion matrix heatmap
- Model accuracy comparison

---
## 📈 Applications
• Fitness Tracking
• Smart Healthcare
• Elderly Monitoring Systems
• Wearable Devices
• Sports Analytics
• IoT-based Smart Systems
---

📌 Conclusion

This project successfully classifies human activities using Machine Learning and Deep Learning techniques. The ANN model demonstrated strong classification performance and highlighted the importance of Deep Learning in real-world sensor-based applications.
