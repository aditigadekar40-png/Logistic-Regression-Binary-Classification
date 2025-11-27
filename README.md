# Binary Classification Using Logistic Regression

## 📌 Overview
This repository contains a Machine Learning experiment to **study and implement Binary Classification using the Logistic Regression algorithm** in Python. The experiment is performed in Google Colab and includes dataset preprocessing, model training, prediction, and evaluation.

---

## 📘 Theory

### 🔹 What is Binary Classification?
Binary classification is a type of supervised machine learning task where the goal is to classify data into **two categories**.  
Examples:  
- Spam vs. Not Spam  
- Disease vs. No Disease  
- Pass vs. Fail  

The output is always **0 or 1** (two possible classes).

---

### 🔹 Logistic Regression Algorithm
Logistic Regression is a statistical model used for **binary classification**.  
It predicts the probability of an input belonging to a class using the **sigmoid function**:

\[
sigmoid(z) = \frac{1}{1 + e^{-z}}
\]

- If probability ≥ 0.5 → Class 1  
- If probability < 0.5 → Class 0  

### 🔹 Steps in Logistic Regression:
1. Import dataset  
2. Clean and preprocess data  
3. Split into training & testing sets  
4. Train Logistic Regression model  
5. Predict on test data  
6. Evaluate using accuracy, confusion matrix, etc.

---

## 🛠️ Tools & Libraries Used
- Python  
- Google Colab  
- NumPy  
- Pandas  
- Matplotlib / Seaborn (optional)  
- Scikit-learn (Logistic Regression model)

---

## 🏃 How to Run
1. Open the notebook in Google Colab  
2. Run all cells  
3. Check accuracy and visualizations
