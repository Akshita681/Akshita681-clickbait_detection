📰 Clickbait Detection using Machine Learning

A Machine Learning project that detects whether a news headline is Clickbait or Not Clickbait using Natural Language Processing (NLP) techniques and a Logistic Regression model.

The system converts text headlines into numerical features using TF-IDF Vectorization and predicts the probability of clickbait content.

📌 Project Overview

Clickbait headlines are designed to attract attention and encourage users to click on links. This project builds a machine learning classifier that analyzes a headline and determines whether it is clickbait or genuine.

The model is trained on a dataset of labeled headlines and learns patterns commonly found in clickbait content.

🚀 Features

✔ Detects clickbait headlines
✔ Uses TF-IDF text vectorization
✔ Machine Learning classification using Logistic Regression
✔ Displays prediction confidence
✔ Easy command-line interaction
✔ Lightweight and beginner-friendly project

🛠 Technologies Used

Python

Scikit-learn

Pandas

NumPy

TF-IDF Vectorizer

Logistic Regression

Joblib / Pickle


🔎 Run Clickbait Prediction

Run the prediction script:

python predictor.py

Example:

Enter a news headline:
You Won’t Believe What Happened Next!

Result: CLICKBAIT
Confidence: 0.91

Example 2:

Enter a news headline:
Government announces new education policy

Result: NOT CLICKBAIT
Confidence: 0.88
🧠 Machine Learning Workflow

Load Dataset

Text Preprocessing

Feature Extraction using TF-IDF

Train Logistic Regression Model

Evaluate Model Accuracy

Save Model and Vectorizer

Predict Clickbait Headlines

📊 Model Used

Logistic Regression

Reasons for using this model:

Works well for text classification

Fast training

Good accuracy for binary classification

Easy to interpret

📦 Requirements

Install the required libraries:

streamlit
scikit-learn
pandas
numpy
matplotlib
seaborn
wordcloud
joblib
🎯 Future Improvements

Add Streamlit Web Interface

Improve dataset size

Try advanced models like:

Random Forest

Naive Bayes

Deep Learning (LSTM/BERT)

Deploy the project online

👩‍💻 Author

Akshita Kamlae
B.Tech Student

⭐ Contributing

Contributions are welcome!

If you want to improve this project:

Fork the repository

Create a new branch

Make improvements

Submit a Pull Request

📜 License

This project is for educational purposes.
