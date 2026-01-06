# 💳 Fraud Detection Streamlit App

A machine learning–based web application that predicts whether a financial transaction is **fraudulent or legitimate**.  
Built using **Python, Scikit-learn, Joblib, and Streamlit**.

---

## 🚀 Overview
This project uses a trained ML pipeline to analyze transaction details and provide real-time fraud predictions through an interactive Streamlit interface.

---

## 🧠 Model
- Trained using historical transaction data  
- Includes preprocessing + classification in one pipeline  
- Saved and loaded using **Joblib**

---

## 🖥️ Tech Stack
- Python  
- Streamlit  
- Pandas  
- Scikit-learn  
- Joblib  

---

## 📂 Files

- fraud_detection.py
- Fraud_Detection.ipynb
- fraud_detection_pipeline.pkl
- requirements.txt

---

## 📁 Dataset

The dataset used in this project is from Kaggle:  
https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset

Before running the notebook or training your model, download the dataset and place it in the project directory.

---

## ▶️ Run the App
```bash
pip install -r requirements.txt
streamlit run fraud_detection.py



