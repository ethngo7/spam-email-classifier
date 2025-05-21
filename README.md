# 📨 Spam Email Classifier

A logistic regression model that predicts whether an email is spam or not based on custom-engineered text features.

## 📌 Project Overview

This project explores how to classify emails as spam or not spam using interpretable, hand-engineered features derived from email content and metadata. The model is trained on a dataset of labeled emails and evaluated using accuracy and AUC.

## 🔍 Features Used

- Presence of HTML tags (`<...>`)
- Special character detection (e.g. `$`, `%`)
- Number of exclamation marks
- Word count and average word length
- Subject line presence and length
- Presence of key words like:  
  `['body', 'business', 'html', 'money', 'offer', 'please', 'form', 'content', 'center']`

## 🧠 Key Results

- Achieved ~90% accuracy on the validation set
- AUC score of ~92%, indicating strong model performance
- Visualizations highlight feature importance and class distribution
- Focused on **interpretable, transparent classification**

## 🛠️ Tools Used

- Python (pandas, scikit-learn, re)
- Logistic Regression
- Jupyter Notebook
- Matplotlib / Seaborn (for plots)

## 📂 Project Files

- `model.pkl` — trained logistic regression model
- `notebook.ipynb` — main analysis, feature engineering, model training
- `requirements.txt` — list of dependencies

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-email-classifier.git
   cd spam-email-classifier
