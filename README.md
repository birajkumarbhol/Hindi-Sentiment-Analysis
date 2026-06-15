# Hindi-Sentiment-Analysis
Machine Learning-based Hindi Movie Review Sentiment Analysis using TF-IDF feature extraction and classification models including Logistic Regression, Naive Bayes, and SVM.
# Hindi Language Sentiment Analysis

## Overview

This project focuses on sentiment classification of Hindi movie reviews using Machine Learning techniques. The objective is to automatically classify reviews into three sentiment categories:

* Positive
* Negative
* Neutral

The project implements a complete Machine Learning pipeline including data preprocessing, feature extraction, model training, evaluation, and comparative analysis.

---

## Dataset

* Dataset: Hindi Movie Reviews Dataset
* Total Reviews: 897
* Language: Hindi
* Classes:

  * Positive
  * Negative
  * Neutral

### Class Distribution

| Sentiment | Samples |
| --------- | ------- |
| Positive  | 293     |
| Negative  | 269     |
| Neutral   | 335     |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning
3. Text Preprocessing
4. Stopword Removal
5. TF-IDF Feature Extraction
6. Model Training
7. Model Evaluation
8. Comparative Performance Analysis

---

## Text Preprocessing

The following preprocessing techniques were applied:

* Removal of special characters
* Removal of unwanted symbols
* Text normalization
* Hindi stopword removal
* Feature extraction using TF-IDF Vectorization

---

## Machine Learning Models

The following Machine Learning algorithms were trained and evaluated:

### 1. Multinomial Naive Bayes

A probabilistic classifier commonly used for text classification tasks.

### 2. Logistic Regression

A linear classification algorithm that achieved the best performance on this dataset.

### 3. Support Vector Machine (SVM)

A supervised learning algorithm used for multi-class sentiment classification.

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Naive Bayes         | 43.89%   |
| Logistic Regression | 60.00%   |
| SVM                 | 55.00%   |

### Best Performing Model

**Logistic Regression** achieved the highest validation accuracy of **60.00%**.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Confusion Matrices

### Logistic Regression

![Logistic Regression](results/lr_confusion_matrix.png)

### Naive Bayes

![Naive Bayes](results/nb_confusion_matrix.png)

### SVM

![SVM](results/svm_confusion_matrix.png)

---

## Repository Structure

```text
Hindi-Sentiment-Analysis/
│
├── data/
│   ├── train.csv
│   └── valid.csv
│
├── notebook/
│   └── Hindi_Sentiment_Analysis.ipynb
│
├── results/
│   ├── nb_confusion_matrix.png
│   ├── lr_confusion_matrix.png
│   └── svm_confusion_matrix.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Future Improvements

* Larger Hindi sentiment datasets
* Feature selection techniques
* Word Embeddings
* Transformer-based language models
* Real-time sentiment prediction system

---

## Author

**Biraj Kumar Bhol**

M.Tech in Computer Science and Engineering (Artificial Intelligence & Machine Learning)

GitHub: https://github.com/birajkumarbhol
