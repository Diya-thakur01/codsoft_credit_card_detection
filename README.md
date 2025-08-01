# Credit Card Fraud Detection 

This machine learning project is built to detect fraudulent credit card transactions using classification models. It helps identify suspicious activities in financial datasets using supervised learning techniques.


# Project Structure

credit_card_fraud_prediction/
├── credit_card_fraud_detection (2).ipynb # Main notebook
├── model.pkl # Trained ML model
├── scaler.pkl # StandardScaler object
├── fraudTrain.csv # Dataset (not pushed to GitHub)
├── results/
│ └── confusion_matrix_rf.png # Confusion Matrix plot
├── README.md # Project documentation
└── requirements.txt # Python dependencies



# Algorithms Used

- Logistic Regression
- Decision Tree
-  Random Forest Classifier (Best performer)

---

# Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- Classification Report

# Output Sample

The confusion matrix image is saved here:
results/confusion_matrix_rf.png

 open it to visually inspect how well the model classifies fraudulent and non-fraudulent transactions.



# How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Diya-thakur01/codsoft_credit_card_detection.git
cd credit_card_fraud_prediction
 
#2. Install dependencies
pip install -r requirements.txt

# 3. Launch the notebook
jupyter notebook

Run all cells in credit_card_fraud_detection (2).ipynb

Dataset Note
The dataset fraudTrain.csv is not uploaded due to size restrictions. Place it manually in the root directory to retrain models.