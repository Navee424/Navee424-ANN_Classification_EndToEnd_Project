# 🚀 Customer Churn Prediction using ANN
## 📌 Project Overview

This project predicts whether a bank customer will churn or not using an Artificial Neural Network (ANN). It is an end-to-end machine learning project covering data preprocessing, model training, and deployment using Streamlit.
---
## 🧠 Problem Statement
Customer churn is a critical problem in the banking industry. This project aims to build a predictive model that helps identify customers likely to leave the bank.
---
## 📊 Dataset
The dataset contains customer details such as:
* Credit Score
* Geography
* Gender
* Age
* Balance
* Number of Products
* Estimated Salary

Target Variable:

* `Exited` → 1 (Churn), 0 (Not Churn)

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas & NumPy
* Streamlit

---

## 🔄 Data Preprocessing

* Label Encoding for Gender
* One-Hot Encoding for Geography
* Feature Scaling using StandardScaler

---

## 🧠 Model Architecture

* Input Layer
* Hidden Layers (Dense + ReLU)
* Output Layer (Sigmoid)

Loss Function: Binary Crossentropy
Optimizer: Adam

---

## 📈 Model Performance

The model predicts churn probability based on input features and outputs a classification result.

---

## 💾 Saved Artifacts

* model.h5
* scaler.pkl
* label_encoder_gender.pkl
* onehot_encoder_geo.pkl

---

## 🌐 Deployment

The model is deployed using Streamlit.

### Run Locally:

```bash
streamlit run app.py
```

---

## ⚠️ Challenges Faced

* TensorFlow compatibility issues during deployment
* Feature mismatch errors
* Dependency management

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Model optimization
* API-based deployment
* Cloud deployment (AWS / Docker)

