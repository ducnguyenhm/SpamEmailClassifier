# 📧 SPAM Email Classification

This project applies and compares three classic machine learning classification methods—**K-Nearest Neighbors (KNN)**, **Logistic Regression**, and **Linear Support Vector Machines (SVM)**—on a real-world SPAM email dataset.

## 🎯 Objectives

1. Build and analyze classification models using KNN, Logistic Regression, and Linear SVM.
2. Use **5-fold cross-validation** to tune model parameters and evaluate performance.
3. Identify underfitting and overfitting through training/testing accuracy comparison.
4. Select optimal model parameters based on generalization performance.
5. Compare models based on accuracy, explainability, and computational efficiency.

---

## 🧠 Classification Methods

| Method                | Tuned Parameter     |
|-----------------------|---------------------|
| K-Nearest Neighbors   | `K` (number of neighbors) |
| Logistic Regression   | `C` (inverse regularization strength) |
| Linear SVM            | `C` (inverse regularization strength) |

---

## 📊 Evaluation Strategy

- **5-Fold Cross-Validation** on the training set to:
  - Identify optimal parameter values
  - Measure average training accuracy
- **Test Set Evaluation** using the best model from cross-validation
- **Overfitting/Underfitting Analysis** by comparing training and testing performance
- **Error Analysis**:
  - Misclassified instances across all models
  - Common vs unique classification errors

---

## 📝 Results Overview

Each classifier was evaluated based on:

- **Accuracy** (training and testing)
- **Confusion Matrix**
- **Explainability**
- **Training/Testing Time**

Final results and justifications for model selection are discussed in the analysis section.

---

## 🧰 Tools & Libraries

- Python 3.x
- scikit-learn
- NumPy
- pandas
- matplotlib / seaborn (for visualization)

---

## 📂 Project Structure

