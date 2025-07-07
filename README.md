# 📧 SpamShield: Hybrid Email Spam Classifier

A machine learning-based project for detecting spam emails using multiple classifiers including K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Naive Bayes, Decision Tree, and a hybrid model combining Naive Bayes with Logistic Regression and SVM.

## 🚀 Project Overview

This project focuses on detecting spam emails using classical machine learning algorithms and explores the power of hybrid modeling for improved accuracy and robustness. The hybrid model leverages Naive Bayes with SVM and Logistic Regression to combine probabilistic learning with discriminative classification.

## 🧠 Algorithms Used

- ✅ K-Nearest Neighbors (KNN)
- ✅ Support Vector Machine (SVM)
- ✅ Naive Bayes
- ✅ Decision Tree
- ✅ Hybrid Model:
  - Naive Bayes + SVM
  - Naive Bayes + Logistic Regression

## 📊 Dataset

We use a labeled dataset of emails consisting of spam and ham (non-spam) messages. The data is preprocessed and vectorized using **TF-IDF** for feature extraction. SMOTE is optionally applied to handle class imbalance.

> Sample columns: `['label', 'message']`

- `label`: "spam" or "ham"
- `message`: actual email content

## ⚙️ Preprocessing Steps

- Text cleaning (lowercasing, punctuation removal, stopword removal)
- Tokenization and lemmatization
- Feature extraction using **TF-IDF**
- Class balancing using **SMOTE**

## 📈 Evaluation Metrics

Each model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve (for selected models)







