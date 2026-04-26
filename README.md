💳 AI-Powered Credit Card Fraud Detection System

🔗 Live Demo: https://credit-card-fraud-detection-1bed.onrender.com

📌 Overview

This project presents a machine learning-based web application designed to detect fraudulent credit card transactions in real time. The system classifies transactions as fraudulent or legitimate using advanced data processing and predictive modeling techniques, accessible through an interactive web interface.

🚨 Problem Statement

With the rapid growth of digital payments, credit card fraud has become a critical concern. Detecting fraud is challenging due to:

Highly imbalanced datasets (fraud cases are rare)
Complex and hidden patterns in transaction behavior

This project aims to build a reliable system that minimizes financial risk by accurately identifying fraudulent transactions.

⚙️ Key Features
🔍 Real-time fraud detection
⚡ Quick test with predefined scenarios
🔬 Advanced transaction input simulation
🎲 Auto-fill sample data for testing
📊 Fraud probability visualization
🧠 Technologies Used
Python
Scikit-learn
Pandas, NumPy
Streamlit
SMOTE (for handling imbalanced data)
🤖 Machine Learning Approach
🔹 Data Preprocessing
Feature scaling using StandardScaler
Handling class imbalance using SMOTE
🔹 Model
Random Forest Classifier
Captures complex patterns
Reduces overfitting
Provides strong performance on imbalanced data
🔹 Evaluation Metrics
Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
🖥️ Application Modules
🏠 Overview

Provides insights into fraud detection and prevention

⚡ Quick Test

Run instant test cases for normal and fraudulent transactions

🔬 Advanced Input

Simulate detailed transaction data and predict fraud probability

📊 How It Works
User inputs transaction details
Data is scaled using a trained scaler
Machine learning model predicts the transaction class
Fraud probability score is displayed
🚀 Future Enhancements
Integration with real-time financial systems
Implementation of deep learning models
Explainable AI for model transparency
Deployment as a REST API
📂 Project Structure
├── app.py
├── fraud_model.pkl
├── scaler.pkl
├── creditcard.ipynb
├── requirements.txt
├── screenshots/
├── demo/
├── confusion_matrix/
└── README.md
📎 Installation (Run Locally)
git clone https://github.com/Reeya0409/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
streamlit run app.py
📚 References
Kaggle Credit Card Fraud Detection Dataset
Scikit-learn Documentation
👩‍💻 Author

Parul Kumari
B.Tech CSE Student | Machine Learning Enthusiast

⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
