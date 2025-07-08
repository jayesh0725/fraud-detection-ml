# 🛡️ Fraud Detection ML System

This project is a machine learning-based fraud detection system that analyzes user transactions and predicts fraudulent behavior. It includes data processing, model training, and a web app built using Flask.

---

## 📌 Features

- Fraud transaction analysis using ML models
- IP address to country mapping
- Device and IP behavior profiling
- Flask dashboard to upload CSV and see predictions
- Reasoning behind each fraud prediction

---

## 🧠 Tech Stack

- Python
- pandas, numpy
- scikit-learn, seaborn, matplotlib
- Flask
- joblib (for saving models)

---

## 🗂️ Files Included

| File | Purpose |
|------|---------|
| `main.py` | Trains the model and saves it as `.pkl` |
| `predict.py` | Flask app for fraud prediction |
| `Fraud_Data.csv` | Dataset used to train the model |
| `IpAddress_to_Country.csv` | IP to country mapping data |
| `rf_model.pkl` | Trained Random Forest model |
| `label_encoder.pkl` | Label encoder used in prediction |
| `README.md` | Project description (this file) |
| `requirements.txt` | List of dependencies |
| `.gitignore` | Files/folders to exclude from Git |

---

## 🚀 How to Run the Project

### 1. Install required libraries
```bash
pip install -r requirements.txt
