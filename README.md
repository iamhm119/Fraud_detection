# Fraud_detection
This project is a Machine Learning-based Fraud Detection System built using Python, Scikit-learn, and Streamlit. It trains a pipeline on transaction data to classify whether a transaction is fraudulent or legitimate.

# 💳 Fraud Detection Prediction App

A **Machine Learning-powered Fraud Detection System** built using **Python, Scikit-learn, and Streamlit**.  
This project predicts whether a given financial transaction is **fraudulent** or **legitimate**, based on transaction details.

---

## 🚀 Features
- End-to-end **ML pipeline** with preprocessing and classification
- Handles categorical & numerical transaction features
- Interactive **Streamlit web app** for real-time prediction
- User inputs:
  - Transaction Type (`PAYMENT`, `TRANSFER`, `CASH-IN`, `CASH-OUT`, `DEPOSIT`)
  - Transaction Amount
  - Sender’s Old & New Balance
  - Receiver’s Old & New Balance

---

## 🛠️ Tech Stack
- **Python 3.11**
- **Scikit-learn** (ML pipeline & model training)
- **Pandas** (data manipulation)
- **Joblib** (model persistence)
- **Streamlit** (web interface)

---

## 📂 Project Structure
fraud-detection/
│── app.py # Streamlit app for fraud prediction
│── fraud_detection.ipynb # Jupyter notebook for model training
│── fraud_detection_pipeline.pkl # Saved ML pipeline
│── requirements.txt # Python dependencies
│── README.md # Project documentation


---

## ▶️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection

2. **Create a virtual environment (recommended)**
     ```bash
    python -m venv venv
    venv\Scripts\activate   # On Windows
    source venv/bin/activate # On Mac/Linux

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

4. **Run the Streamlit app**
   ```bash
   python -m streamlit run app.py

5. Open in browser
Streamlit will show a local URL like:
  ```bash
  Local URL: http://localhost:8501










