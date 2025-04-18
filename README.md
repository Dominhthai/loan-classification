# 💼 Loan Classification Project

## 📌 Overview

This project aims to predict whether an individual should be granted a loan by a bank, based on various applicant attributes. The target variable for prediction is `Loan_status`.

We employ two distinct modeling approaches:

1. **Traditional Machine Learning Classifiers**: Utilizing algorithms from Scikit-Learn.
2. **Artificial Neural Network (ANN)**: A custom-built neural network trained on GPU.

---

## 🧠 Methodology

### 1. Machine Learning Classifiers

We explore and evaluate several classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- **XGBoost** (achieved the highest accuracy)

### 2. Artificial Neural Network (ANN)

Key features of the ANN approach:

- **Training**: Conducted over 100 epochs on GPU.
- **Model Checkpointing**: Saves the best model based on highest accuracy achieved during training.
- **Regularization**: Implements L1 regularization to prevent overfitting.

---

## 📊 Evaluation Metrics

To assess model performance, we utilize the following metrics:

- **Accuracy**: Overall correctness of the model.
- **Precision**: Correct positive predictions relative to total positive predictions.
- **Recall**: Correct positive predictions relative to actual positives.
- **F1-Score**: Harmonic mean of precision and recall.

---

## 🏆 Results

- The **XGBoost classifier** outperformed other models, achieving an accuracy of **94%**.
- The ANN model demonstrated competitive performance, with accuracy improving over epochs due to effective regularization and model checkpointing.

---

## 📁 Project Structure

