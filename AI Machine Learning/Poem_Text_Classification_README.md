# Poem Text Classification

## Overview

A text classification model that categorizes poems by genre using NLP techniques. The model demonstrates a complete NLP pipeline — from raw text through cleaning, feature extraction, model training, and evaluation.

---

## How It Works

1. **Data cleaning:** Remove punctuation, stopwords, and normalize text
2. **Feature extraction:** TF-IDF vectorization to convert poems into numerical features
3. **Classification:** Multi-class classification model trained to predict poem genre
4. **Evaluation:** Accuracy, precision, recall, confusion matrix per genre class

---

## Model Performance

- **Algorithm:** SVM / Logistic Regression (Scikit-learn)
- **Vectorizer:** TF-IDF
- **Test accuracy:** ~93%
- **Task:** Multi-class poem genre classification

---

## Technologies Used

- **Python:** Pandas, Scikit-learn, NLTK
- **NLP:** TF-IDF Vectorizer, lemmatization, stopword removal
- **Development:** Visual Studio Code, Google Colab
