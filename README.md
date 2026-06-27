📧 Spam Mail Detector using Machine Learning

A Machine Learning project that classifies SMS messages as Spam or Ham (Not Spam) using Natural Language Processing (NLP) and supervised machine learning techniques. The project leverages TF-IDF Vectorization for feature extraction and compares the performance of Multinomial Naive Bayes and Logistic Regression classifiers.

---

🚀 Project Overview

Spam messages are a common problem in digital communication. This project demonstrates how Machine Learning can automatically identify unwanted SMS messages by learning patterns from labeled data.

The model is trained on the UCI SMS Spam Collection Dataset and follows a complete machine learning workflow—from data preprocessing to model evaluation and prediction.

---

✨ Features

- Data loading and exploration
- Text preprocessing using NLTK
  - Lowercasing
  - Tokenization
  - Stopword removal
- Feature extraction using TF-IDF Vectorizer
- Spam/Ham message classification
- Model training with:
  - Multinomial Naive Bayes
  - Logistic Regression
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Custom SMS prediction

---

🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

🤖 Machine Learning Models

- Multinomial Naive Bayes
- Logistic Regression

---

📂 Dataset

UCI SMS Spam Collection Dataset

- Total Messages: 5,572
- Categories:
  - Ham – Legitimate Messages
  - Spam – Unwanted Promotional Messages

---

📊 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore and inspect the data
4. Preprocess text using NLTK
5. Convert text into numerical features using TF-IDF
6. Split the dataset into training and testing sets
7. Train the machine learning models
8. Evaluate model performance
9. Predict whether a custom message is Spam or Ham

---

📈 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

📁 Project Structure

Spam-Mail-Detector-ML/
│
├── Spam_Mail_Detector.ipynb
├── SMSSpamCollection
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore

---

⚙️ Installation

Clone the repository:

git clone https://github.com/<your-github-username>/spam-mail-detector-ml.git

Move to the project directory:

cd spam-mail-detector-ml

Install the required dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

---

🔮 Future Enhancements

- Build a web application using Flask or Streamlit
- Deploy the trained model online
- Improve performance with advanced NLP techniques
- Extend support for email spam detection

---

👨‍💻 Author

Mayank Khare

B.Tech Student | Python & Machine Learning Enthusiast
