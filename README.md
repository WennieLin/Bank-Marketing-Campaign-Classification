# Bank-Marketing-Campaign-Classification

This project explores and compares several classification algorithms to predict whether a customer will subscribe to a term deposit based on data from a Portuguese banking institution.

## 📊 Dataset
The dataset contains information from **17 marketing campaigns** conducted between **May 2008 and November 2010**, including personal, financial, and contact-related client data.

- Source: `bank-additional-full.csv`
- Target variable: `y` (yes/no – whether the client subscribed to a term deposit)

## 🎯 Business Objective
Improve the efficiency of telemarketing campaigns by identifying high-potential clients, reducing unnecessary calls, and optimizing resource allocation.

## 🛠️ Methods

### 1. Data Preparation
- Selected bank client-related features (e.g., age, job, education).
- One-hot encoding for categorical variables.
- Standard scaling for numeric variables.

### 2. Baseline Model
- Calculated baseline accuracy using the majority class.

### 3. Models Compared
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)

Each model was evaluated based on:
- Training time
- Training accuracy
- Test accuracy

### 4. Performance Evaluation
- Accuracy
- Confusion Matrix
- Classification Report

## ⚙️ Next Steps
- Feature engineering (e.g., drop low-impact features like gender if applicable)
- Hyperparameter tuning using GridSearchCV
- Address class imbalance using techniques like SMOTE or class weighting

## 📁 Files
- `bank-additional-full.csv`: Dataset
- `model_comparison.ipynb`: Jupyter Notebook with all modeling steps
- `README.md`: Project description


