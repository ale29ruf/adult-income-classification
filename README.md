# 🧠 Income Classification using the Adult Census Income Dataset

This project focuses on predicting an individual's income level based on demographic and socio-economic attributes using machine learning models.  
The analysis is entirely performed through a Google Colab notebook and leverages data preprocessing, neural networks, and custom evaluation metrics.

---

## 📌 Project Objective

The goal is to build a binary classification model capable of predicting whether a person earns:

- **≤ 50K USD**  
- **> 50K USD**

The model is trained on the widely used **Adult Census Income dataset** (32,561 samples, 15 attributes).

---

## 📂 Dataset Overview

### **Numerical Features**
- age  
- fnlwgt  
- education.num  
- capital.gain  
- capital.loss  
- hours.per.week  

### **Categorical Features**
- workclass  
- education  
- marital.status  
- occupation  
- relationship  
- race  
- sex  
- native.country  

### **Target**
- `income`: binary (`<=50K` or `>50K`)

---

## 🧹 Data Preprocessing

The following preprocessing steps were applied:

### ✔️ Missing data handling  
Cleaning/removing inconsistent values.

### ✔️ Encoding  
- One-Hot Encoding for multi-category fields  
- Binary encoding for the target variable  

### ✔️ Feature scaling  
Normalization of numerical features to improve neural network convergence.

data.info()
data.describe()
