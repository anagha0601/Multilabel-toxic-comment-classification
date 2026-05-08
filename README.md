# Multi-label Toxic Comment Classification

## 📌 Overview

This project builds an end-to-end Natural Language Processing (NLP) and Machine Learning (ML) pipeline to classify toxic comments into multiple categories and detect group-targeted hate speech. It leverages TF-IDF vectorization and advanced text preprocessing techniques to handle noisy, real-world text data.

The model supports **multi-label classification**, meaning a single comment can belong to multiple toxicity categories simultaneously.

---

## 🚀 Features

* Multi-label classification of toxic comments
* Detection of group-targeted hate speech
* Advanced text preprocessing (cleaning, normalization, tokenization)
* TF-IDF based feature extraction
* Scalable ML pipeline
* Handles imbalanced datasets

---

## 🧠 Problem Statement

Online platforms often struggle to moderate toxic content effectively. Comments may contain multiple forms of toxicity such as:

* Insults
* Threats
* Hate speech
* Obscene language

This project aims to automatically classify such comments into multiple categories to assist in content moderation.

---

## 🏗️ Pipeline Architecture

1. **Data Collection**
2. **Text Preprocessing**

   * Lowercasing
   * Removing punctuation & special characters
   * Stopword removal
   * Lemmatization/Stemming
3. **Feature Extraction**

   * TF-IDF Vectorization
4. **Model Training**

   * Multi-label classification models - Logistic Regression
5. **Evaluation**

   * Precision, Recall, F1-score
6. **Prediction**

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas, NumPy
* NLTK / SpaCy
* Matplotlib / Seaborn (for visualization)

---

## 📊 Dataset

* Typically uses datasets like the **Jigsaw Toxic Comment Classification Dataset**
* Contains labeled comments across multiple toxicity categories


## 📈 Evaluation Metrics

* Accuracy (subset accuracy)
* Precision
* Recall
* F1-score
* Hamming Loss

---

## 📌 Results

* Achieved strong performance using TF-IDF + classical ML models
* Demonstrates effectiveness in detecting overlapping toxicity labels

---

## 🔮 Future Improvements

* Use deep learning models (LSTM, BERT)
* Improve handling of context and sarcasm
* Deploy as an API or web app


## ⭐ Acknowledgements

* Jigsaw / Google Perspective API dataset
* Open-source NLP community
