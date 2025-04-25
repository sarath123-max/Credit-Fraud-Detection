
---

# 💳 Credit Card Fraud Detection

This project builds a machine learning model to detect fraudulent credit card transactions. The dataset used is **highly imbalanced**, making fraud detection challenging. To address this, techniques like **SMOTE** are used to synthetically oversample the minority class, enabling more robust fraud detection.

---

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Scikit-learn** – ML modeling & evaluation
- **SMOTE (Imbalanced-learn)** – Class imbalance handling
- **Matplotlib**, **Seaborn** – Data visualization

---

## 📊 Key Features

- 📏 Feature scaling using `StandardScaler` for consistent model inputs  
- ⚖️ Class imbalance handled using **SMOTE**  
- 🌲 Model training with **RandomForestClassifier**  
- 📈 Model evaluation using:
  - Confusion Matrix  
  - Precision, Recall  
  - F1-Score  

---

## 🧪 Results

- Achieved strong performance on **imbalanced** credit card transaction data  
- The model effectively detects **rare fraudulent activities** among legitimate transactions

---

## 📁 Dataset

Dataset is publicly available on Kaggle:

🔗 [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🖥️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. **Add the dataset**:
   Place the `creditcard.csv` file in the same directory as your script or notebook.

3. **Run the script**:
   ```bash
   python fraud_detection.py
   ```

> You can also run the Jupyter notebook version if preferred:
```bash
jupyter notebook fraud_detection.ipynb
```

---

## 📬 Contact

For questions, contributions, or suggestions, feel free to [open an issue](https://github.com/yourusername/credit-card-fraud-detection/issues) or contact me via GitHub.

---

