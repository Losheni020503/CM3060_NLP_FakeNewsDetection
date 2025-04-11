# 📰 Fake News Detection with LSTM and SVM

This project focuses on detecting **fake news** using Natural Language Processing (NLP). We use the ["Fake and Real News"](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) dataset from Kaggle and implement two classification models:

- 🔹 **Support Vector Machine (SVM)** – A traditional ML approach using TF-IDF
- 🔹 **Long Short-Term Memory (LSTM)** – A deep learning model for sequential data
  
---

## 📌 Objectives

- Build a complete NLP pipeline for fake news detection.
- Compare traditional machine learning vs deep learning models.
- Optimize model performance using preprocessing and hyperparameter tuning.

---

## 🧠 Models Overview

### 🔸 Support Vector Machine (SVM)
- Uses **TF-IDF vectorization** on article text.
- Trained with a linear kernel for binary classification.
- Evaluated using accuracy, precision, recall, and F1-score.

### 🔸 Long Short-Term Memory (LSTM)
- Text data tokenized and padded into sequences.
- Used an Embedding layer + LSTM layer for feature extraction.
- Final layer is a sigmoid neuron for binary classification.
- Tuned with different batch sizes, dropout rates, and epochs.

---

## 🚀 Key Takeaways
LSTM outperformed SVM in terms of accuracy and F1-score.

Deep learning is powerful for sequential text classification tasks.

Proper preprocessing significantly boosts model performance.

## Author
- Losheni
- Student at University of London , Singapore Institute of Management
- Reach me at: losheni.ms@gmail.com


