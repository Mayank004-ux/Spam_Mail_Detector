#Spam Mail Detector using Machine Learning

##Overview

The Spam Mail Detector is a Machine Learning project developed using Python and Scikit-learn to classify SMS messages as Spam or Ham (Not Spam). The project uses Natural Language Processing (NLP) techniques for text preprocessing and TF-IDF Vectorization for feature extraction. Two machine learning algorithms—Multinomial Naive Bayes and Logistic Regression—are trained and evaluated to classify messages accurately.

---

##Features

- Load and explore the SMS Spam dataset
- Text preprocessing using NLTK
  - Lowercasing
  - Tokenization
  - Stopword removal
- TF-IDF Vectorization
- Train and test machine learning models
- Spam/Ham message classification
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Predict custom SMS messages

---

##Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

##Machine Learning Algorithms

- Multinomial Naive Bayes
- Logistic Regression

---

##Dataset

UCI SMS Spam Collection Dataset

- Total Messages: 5,572
- Classes:
  - Ham (Legitimate Messages)
  - Spam (Unwanted Messages)

---

##Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Handle Missing Values
5. Visualize Dataset
6. Preprocess Text using NLTK
7. Convert Text into Numerical Features using TF-IDF
8. Split Dataset into Training and Testing Sets
9. Train Naive Bayes Model
10. Train Logistic Regression Model
11. Evaluate Model Performance
12. Predict Custom Messages

---

##Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

##Project Structure

Spam-Mail-Detector-ML/
│
├── Spam_Mail_Detector.ipynb
├── SMSSpamCollection
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore

---

##Installation

Clone the repository:

git clone https://github.com/your-username/spam-mail-detector-ml.git

Navigate to the project folder:

cd spam-mail-detector-ml

Install the required libraries:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

---

Future Improvements

- Develop a web application using Flask or Streamlit
- Deploy the model for real-time spam detection
- Extend the project for email spam classification
- Improve performance using advanced NLP and deep learning models

---

Author

Mayank Khare

B.Tech Student | Machine Learning Enthusiast
