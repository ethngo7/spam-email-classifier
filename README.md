# 📨 Spam Email Classifier (to see full code, look for the .ipynb file in folder in the "spam-email-classifier" folder)

A logistic regression model that predicts whether an email is spam or not based on custom-engineered text features.

## 📌 Project Overview

This project explores how to classify emails as spam or not spam using interpretable, hand-engineered features derived from email content and metadata. The model is trained on a dataset of labeled emails and evaluated using accuracy and AUC.

## Features Used

- Presence of HTML tags (`<...>`)
- Special character detection (e.g. `$`, `%`)
- Number of exclamation marks
- Word count and average word length
- Subject line presence and length
- Presence of key words like:  
  `['body', 'business', 'html', 'money', 'offer', 'please', 'form', 'content', 'center']`

## 📊 Key Results

- Achieved ~90% accuracy on the validation set
- AUC score of ~92%, indicating strong model performance
- Visualizations highlight feature importance and class distribution
- Focused on **interpretable, transparent classification**

ROC Curve:
  <img width="589" alt="Screenshot 2025-06-11 at 13 52 53" src="https://github.com/user-attachments/assets/e504b2d6-9486-45b1-95e2-3148a6337a04" />


## 🧠 Tools Used

- Python (pandas, scikit-learn, re, etc.)
- Logistic Regression
- Jupyter Notebook
- Matplotlib / Seaborn (for plots)

## Project Files

- `spam_email_classifier.ipynb` — The actual project containing the main analysis, feature engineering, model training
- `model.pkl` — trained logistic regression model
- `spam_ham_data.zip` — datasets


## Author

Ethan Ngo  
UC Berkeley — Data Science Major  
[LinkedIn](https://www.linkedin.com/in/ethngo7)
