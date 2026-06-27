# Spam Mail Detector using Machine Learning

## Overview

This project is a Machine Learning-based Spam Mail Detector that classifies SMS messages as **Spam** or **Ham (Not Spam)**. It uses Natural Language Processing (NLP) techniques to preprocess text and applies machine learning algorithms for classification.

The project is implemented in **Python** using **Jupyter Notebook** and trained on the **UCI SMS Spam Collection Dataset**.

---

## Features

- Text preprocessing
  - Lowercasing
  - Tokenization
  - Stopword removal
- TF-IDF Vectorization
- Spam/Ham classification
- Naive Bayes Classifier
- Logistic Regression Classifier
- Model performance evaluation
- Confusion Matrix
- Classification Report
- Custom message prediction

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## Machine Learning Algorithms

- Multinomial Naive Bayes
- Logistic Regression

---

## Dataset

**Dataset:** UCI SMS Spam Collection Dataset

It contains over **5,500 SMS messages** labeled as:
- Spam
- Ham

---

## Project Workflow

1. Load Dataset
2. Data Exploration
3. Text Preprocessing
4. Feature Extraction using TF-IDF
5. Train-Test Split
6. Model Training
7. Prediction
8. Performance Evaluation
9. Custom Spam Detection

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```
Spam-Mail-Detector-ML/
│
├── Spam_Mail_Detector.ipynb
├── SMSSpamCollection
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Mayank004-ux/Spam_Mail_Detector
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- Build a web application using Flask or Streamlit
- Deploy the model online
- Support email spam detection
- Improve accuracy using advanced NLP models

---

## Author

**Mayank Khare**

B.Tech Student | Machine Learning Enthusiast
