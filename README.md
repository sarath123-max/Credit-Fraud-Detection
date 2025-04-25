💳 Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning. The dataset used is highly imbalanced, so special techniques like SMOTE are applied for effective fraud detection.


🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- SMOTE (Imbalanced-learn)
- Matplotlib, Seaborn

---

📊 Key Features
- Feature scaling using `StandardScaler` for consistent model input.
- Synthetic oversampling using `SMOTE` to handle class imbalance.
- Model training using `RandomForestClassifier`.
- Evaluation with Confusion Matrix, Precision, Recall, and F1-score.

---

🧪 Results
- Achieved strong classification performance on imbalanced data.
- Fraud detection model capable of identifying rare transaction anomalies.

---

📁 Dataset
- [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

🖥️ How to Run
1. Clone the repository  
2. Place the `creditcard.csv` file in the same directory  
3. Run the notebook or script:  
   ```bash
   python fraud_detection.py
