
# Toxic Comment Classification

A multi-label text classification project using deep learning to detect various types of toxic comments. Built with GloVe word embeddings and a hybrid Bi-GRU + CNN model for high accuracy.

---

## 🧠 Problem Statement

Given a dataset of comments, classify each comment into multiple possible categories such as:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

This is a **multi-label** classification problem where a comment can belong to more than one class.

---

## 📊 Dataset

- Source: [Jigsaw Toxic Comment Classification Challenge (Kaggle)](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)
- Contains 150k+ comments with six binary labels

---

## 🛠️ Tech Stack

- Python
- Keras + TensorFlow
- GloVe embeddings (100D)
- Bi-GRU, 1D CNN
- Scikit-learn for evaluation

---

## 🧪 Model Architecture

- Input → Embedding Layer (GloVe)
- → BiGRU
- → 1D CNN
- → Dense + Sigmoid for multi-label output

---



