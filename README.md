# Spam Mail Detection using Machine Learning

## Overview

This project builds a **Spam Email Detection System** using **Machine Learning**.
The model classifies emails into:

* **Spam (0)**
* **Ham (1)**

The system uses **TF-IDF Vectorization** to convert text into numerical features and **Logistic Regression** for classification.

---

## Dataset

The dataset contains labeled emails with two columns:

* **Category** → spam or ham
* **Message** → email text

Example:

| Category | Message                                   |
| -------- | ----------------------------------------- |
| ham      | I'm going to attend the meeting tomorrow  |
| spam     | Congratulations! You've won a free ticket |

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Label Encoding
4. Train-Test Split
5. Text Vectorization using **TF-IDF**
6. Model Training using **Logistic Regression**
7. Model Evaluation
8. Spam Prediction System

---

## Feature Extraction

Text messages are converted into numerical vectors using:

TF-IDF (Term Frequency – Inverse Document Frequency)

This helps the model identify important words while reducing the impact of common words.

---

## Model

Algorithm used:

**Logistic Regression**

Reasons:

* Efficient for text classification
* Works well with high-dimensional sparse data
* Fast training

---

## Model Evaluation

Metrics used:

* Accuracy Score
* Training Accuracy
* Test Accuracy

Accuracy on training data: 0.96
Accuracy on test data: 0.97


