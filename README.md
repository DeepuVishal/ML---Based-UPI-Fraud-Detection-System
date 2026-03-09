# SmartUPI: Intelligent ML-Based Fraud Detection System

### 🚀 Overview
**SmartUPI** is a real-time fraud detection framework developed for the **Anna University Final Year Project**. It uses advanced machine learning to identify suspicious UPI transactions and provide an administrative forensic dashboard.

### 🛠️ Technical Evolution (Review 1 to Review 2)
- **Algorithm Shift:** Upgraded from **Isolation Forest** (Unsupervised) to **XGBoost Classifier** (Supervised) for higher precision and better handling of imbalanced datasets.
- **Enhanced Logic:** Integrated **Boolean Feature Engineering** for `Is_Weekend` and `Is_Night` detection patterns.

### 📂 Repository Structure
- `app.py`: Main Streamlit User Interface.
- `train_model.py`: Logic for training the XGBoost engine.
- `dataset/`: Contains the transaction logs (`fraud_data.csv`).
- `models/`: Pre-trained `.pkl` files and label encoders.
- `requirements.txt`: List of necessary Python libraries.

### 🔑 Credentials & Access
- **Admin Portal:** Accessible via the Sidebar.
- **Secure Key:** `CDE/2026`

### 📊 How to Run
1. Clone this repository.
2. Install dependencies: 
   ```bash
   pip install -r requirements.txt
