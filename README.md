# 📧 Email Spam Detection Using Machine Learning

A machine learning project that classifies text messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and the **Multinomial Naive Bayes** algorithm.

## 📌 Project Overview

Spam messages are unwanted messages that may contain advertisements, scams, or other irrelevant content. This project builds a machine learning model that automatically identifies whether a message is spam or legitimate.

The project uses:

- **Pandas** for data handling
- **CountVectorizer** for converting text into numerical features
- **Multinomial Naive Bayes** for classification
- **Accuracy Score** for model evaluation
- **Confusion Matrix** for analyzing predictions

## 🎯 Objective

The objective of this project is to build a classification model that can predict whether an email/message belongs to one of two classes:

| Value | Class |
|---|---|
| `0` | Ham / Not Spam |
| `1` | Spam |

## 📂 Dataset

The project uses a dataset named:

```text
spam.csv