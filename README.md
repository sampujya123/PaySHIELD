# PaySHIELD: Fraud Analysis in UPI Transactions Using Hybrid Models

PaySHIELD is a hybrid machine learning framework developed to detect fraudulent UPI transactions using ensemble learning, deep learning, and NLP-based risk analysis. The system combines structured transaction analysis with text-based fraud reasoning to improve fraud detection accuracy, enhance fraud recall, and support explainable decision-making.

---

## Overview

With the rapid growth of UPI transactions, digital payment platforms have become increasingly vulnerable to sophisticated financial frauds. Traditional machine learning approaches often struggle with evolving fraud patterns, highly imbalanced datasets, and the lack of transparency in predictions.

PaySHIELD addresses these challenges through a hybrid architecture that integrates multiple machine learning models with explainable AI techniques to provide accurate and interpretable fraud detection.

---

## Key Features

- Hybrid fraud detection framework using multiple models
- Weighted soft voting ensemble approach
- NLP-based scam signal detection using DistilBERT
- Explainable AI integration using SHAP and LIME
- Risk-based transaction categorization
- SMOTE-based class imbalance handling
- Fraud probability scoring and analysis

---

## Technologies Used

### Programming & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Imbalanced-learn (SMOTE)

### Development Tools
- Google Colab
- VS code
- GitHub

---

## System Architecture

The PaySHIELD framework follows a multi-stage fraud detection pipeline:

1. Data preprocessing and feature engineering  
2. Class balancing using SMOTE  
3. Multi-model prediction pipeline  
4. Weighted soft voting fusion  
5. Risk classification  
6. Explainable AI analysis  

### Core Models
- Calibrated Random Forest
- Multi-Layer Perceptron (MLP)
- DistilBERT for transaction text analysis

---

## Dataset Details

- Total Transactions: 250,000
- Fraudulent Transactions: 5,008
- Legitimate Transactions: 244,992

### Data Features
- Numerical transaction features
- Categorical attributes
- Text-based transaction notes

---

## Performance Metrics

| Metric | Score |
|---|---|
| Recall | 88.12% |
| ROC-AUC | 0.9519 |
| Accuracy | 96.05% |
| PR-AUC | 0.6127 |

The hybrid weighted voting framework significantly improved fraud recall while maintaining strong overall classification performance.

---

## Explainable AI Integration

PaySHIELD incorporates Explainable AI (XAI) techniques to improve transparency and interpretability in fraud detection.

- **SHAP** is used for global feature importance analysis
- **LIME** is used for local prediction-level explanations

These methods help understand the reasoning behind fraud predictions and support better auditing and verification.

---

## Future Enhancements

- Real-time fraud detection pipeline
- Streamlit-based deployment
- Graph Neural Network integration
- Continuous model retraining
- Real-time monitoring dashboard

---

## Authors

- Sampujya Musunuri  
- N. Indu Priya  

### Institution
Chaitanya Bharathi Institute of Technology (CBIT)

### Project Supervisor
Smt. G. Shanmukhi Rama
