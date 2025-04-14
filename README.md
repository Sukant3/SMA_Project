# SMA : Mini-Project 

# Credit Card Fraud Detection using Machine Learning

This project detects fraudulent credit card transactions using machine learning models. It uses real-world transaction data and provides a user-friendly interface via Streamlit.
________________________

## 📊 Dataset

- Rows:284,807  
- Columns: 31  
- Target: 'Class'(0 = Legit, 1 = Fraud)
  ___________________________________

## 🧠 Algorithms Used

- Logistic Regression – Baseline classification model.
- Isolation Forest – Detects anomalies using isolation mechanism.
- Local Outlier Factor (LOF) – Detects outliers based on local density.
- Support Vector Machine (SVM) – Separates data using optimal hyperplanes.
  _______________________________________

## 📈 Evaluation

Model performance is measured using accuracy_score from scikit-learn for both training and testing datasets.
_______________________

## 💻 Streamlit App

- Upload CSV with transaction data.
- Predict if a transaction is fraudulent or legitimate.
- Interactive and real-time detection.
______________________

## ✅ Conclusion

The models achieved high accuracy, especially logistic regression and Isolation Forest. The Streamlit app enables real-time fraud detection through a simple UI.

____________
🤝 Contributing

Contributions, issues, and feature requests are welcome!
