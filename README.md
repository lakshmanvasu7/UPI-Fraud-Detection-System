# 💳 UPI Fraud Detection System

This project is a real-time fraud detection system developed using machine learning algorithms to identify suspicious transactions in UPI (Unified Payments Interface). It includes a Streamlit-based web app and uses a trained XGBoost model to predict fraudulent activity based on transaction data.

---

## 🎯 Project Objective

The goal is to enhance the security of UPI transactions by analyzing patterns such as transaction type, gateway, state, merchant category, and amount to detect fraud in real-time.

---

## 📌 Features

* Detects fraudulent UPI transactions with high accuracy
* Provides real-time fraud alerts for individual and bulk transactions
* Supports CSV upload for large-scale transaction checks
* Interactive web app interface built with Streamlit
* Achieves \~95% accuracy using XGBoost algorithm

---

## 🧠 Machine Learning Overview

* **Model Used**: XGBoost (Gradient Boosting)
* **Trained On**: Realistic UPI transaction dataset
* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score

---

## 🛠️ Tech Stack

* **Frontend**: Streamlit
* **Backend/ML**: Python, XGBoost, pandas, scikit-learn
* **Tools**: Jupyter Notebook, Pickle
* **Libraries**: numpy, base64, datetime, streamlit, pandas, xgboost

---

## 🚀 Getting Started

### Prerequisites

* Python 3.7+

### Installation

```bash
git clone https://github.com/lakshmanvasu7/UPI-Fraud-Detection.git
cd UPI-Fraud-Detection

# (Recommended) Setup virtual environment
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run streamlit_app.py
```

Visit `http://localhost:8501` to use the app.

---

## 📁 Project Structure

```
UPI-Fraud-Detection/
├── streamlit_app.py                        # Main Streamlit application
├── UPI Fraud Detection Final.pkl           # Trained ML model
├── UPI_FRAUD_DETECTION_CAPSTONE_PROJECT.ipynb # Model development notebook
├── sample.csv                              # Sample transaction dataset
├── requirements.txt                        # Project dependencies
└── README.md                               # Project documentation
```

---

## 🧪 Evaluation & Performance

* **Accuracy**: 95%
* **Precision**: High – few false positives
* **Recall**: High – detects majority of frauds
* **F1-Score**: Balanced precision and recall

Confusion matrix and classification reports were used to validate model robustness. Bulk and individual predictions are supported.

---

## 📚 Based On Capstone Project

This system is part of the final submission for:
**Application Development - II**
Bachelor of Technology – ECE (2022–2026)
Malla Reddy College of Engineering & Technology, Hyderabad

Project Guide: **Mr. V. Shiva Raj Kumar** (Assistant Professor)

---

## 👨‍💻 Author

**Lakshman Vasu Manda**

* GitHub: [lakshmanvasu7](https://github.com/lakshmanvasu7)
* Email: [vaasu.a3aa@gmail.com](mailto:vaasu.a3aa@gmail.com)

---

## ⚖️ License

This project is open-source and available under the MIT License.
