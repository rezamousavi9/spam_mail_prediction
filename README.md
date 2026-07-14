# 📧 Spam Mail Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![License](https://img.shields.io/badge/License-MIT-red.svg)

A Machine Learning project that classifies SMS/Email messages as Spam or Ham (Not Spam) using TF-IDF Vectorization and Logistic Regression.

---

## 📌 Project Overview

Spam messages are one of the most common problems in digital communication. This project builds a binary text classification model capable of automatically detecting whether a message is Spam or Ham.

The workflow includes:

- Data preprocessing
- Feature extraction with TF-IDF
- Logistic Regression model training
- Model evaluation
- Prediction on custom messages

---

## 🚀 Features

- Text preprocessing
- Missing value handling
- Label encoding
- Train/Test split
- TF-IDF feature extraction
- Logistic Regression classifier
- High prediction accuracy
- Predict custom messages

---

## 📂 Project Structure
spam_mail_prediction/
│
├── spam_mail_prediction.ipynb
├── mail_data.csv
├── README.md
└── requirements.txt

---

## 🛠 Technologies

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The project uses the SMS Spam Collection Dataset, containing 5,572 labeled SMS messages.

Classes:

- Ham (1) → Legitimate message
- Spam (0) → Unwanted message

---

## ⚙️ Machine Learning Pipeline
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Label Encoding
   │
   ▼
Train/Test Split
   │
   ▼
TF-IDF Vectorizer
   │
   ▼
Logistic Regression
   │
   ▼
Prediction

---

## 📈 Model Performance

| Metric | Score |
|---------|-------|
| Training Accuracy | 96.77% |
| Test Accuracy | 96.68% |

The model generalizes well with very similar training and testing accuracy, indicating minimal overfitting.

---

## 💻 Installation

Clone the repository
git clone https://github.com/rezamousavi9/spam_mail_prediction.git

Move to the project directory
cd spam_mail_prediction

Install dependencies
pip install -r requirements.txt

Launch Jupyter Notebook
jupyter notebook

Open
spam_mail_prediction.ipynb

Run all cells.

---

## 🧪 Example Prediction

Input
I've been searching for the right words to thank you for this breather...

Output
Ham Mail

Example Spam
Congratulations!
You have won a FREE iPhone.
Click here to claim your prize.

Output
Spam Mail

---

## 🧠 Model

The project uses Logistic Regression, a fast and effective linear classification algorithm for binary text classification.

Text messages are transformed into numerical vectors using TF-IDF Vectorizer, which assigns higher importance to informative words while reducing the impact of common words.

---

## 📌 Future Improvements

- Deploy using Streamlit
- Save trained model using Joblib
- Hyperparameter tuning
- Try Naive Bayes, SVM, Random Forest
- Add confusion matrix and classification report
- Build REST API with FastAPI

---

## 👨‍💻 Author

Reza Mousavi

GitHub:
https://github.com/rezamousavi9

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
