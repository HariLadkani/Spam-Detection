# Email Spam Detection with Flask and Naive Bayes Classifier

This project aims to detect spam emails using a machine learning model implemented with Python and Flask. The system uses a **Naive Bayes Classifier** trained on a dataset of emails to classify messages as spam or ham (non-spam).

## Introduction

Email spam has become a major problem with the rapid growth of internet users. Spammers send emails for illegal or unethical purposes, such as phishing, fraud, and spreading malicious links. This project applies machine learning techniques to identify and filter spam emails with high accuracy and precision.

---

## Features

- Preprocesses email data to train a **Naive Bayes Classifier**.
- Allows users to input an email message through a web interface.
- Predicts whether the email is **spam** or **ham** using the trained model.
- Provides a simple and intuitive UI built with Flask.

---

## Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS (via `render_template`)
- **Machine Learning:** 
  - CountVectorizer (feature extraction)
  - Naive Bayes Classifier (classification)
  - Pandas, Scikit-learn (data processing and modeling)

