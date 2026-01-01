# CODSOFT Machine Learning Internship

This repository contains the Machine Learning projects completed during my internship at **CODSOFT**. The tasks involve Natural Language Processing (NLP) for text classification and handling imbalanced datasets in financial fraud detection.

---

## 📋 Project Summary

| Task | Domain | Algorithms | Key Techniques | Best Accuracy |
| :--- | :--- | :--- | :--- | :--- |
| **Genre Classification** | NLP | Naive Bayes, Logistic Regression | TF-IDF, Count Vectorizer | **59.38%** |
| **Card Fraud Detection** | Finance | Random Forest, Decision Tree | SMOTE, Target Encoding | **54.94%** |
| **SMS Spam Detection** | NLP | Naive Bayes | SMOTE, TF-IDF | **98.59%** |

---

## 📂 Detailed Task Overview

### 1. Movie Genre Classification
**Objective:** Classify movie genres based on their plot summaries using NLP.

* **Approach:** Extracted the 'plot' (Features) and 'genre' (Labels).
* **Vectorization:** Implemented and compared **Count Vectorizer** and **TF-IDF Vectorizer**.
* **Models:** Trained Logistic Regression and Naive Bayes across both vectorization methods.
* **Performance:**
    * Naive Bayes (Count): 0.5255
    * Naive Bayes (TF-IDF): 0.4426
    * Logistic Regression (Count): 0.4579
    * **Logistic Regression (TF-IDF): 0.5938**



### 2. Credit Card Fraud Detection
**Objective:** Identify fraudulent transactions in a highly imbalanced dataset.

* **Preprocessing:** Cleaned data, removed redundant features, and applied **Target Encoding** to categorical variables.
* **Class Imbalance:** Used **SMOTE** (Synthetic Minority Over-sampling Technique) to generate synthetic samples for the minority (fraud) class.
* **Models:** Random Forest and Decision Tree.
* **Performance:**
    * Decision Tree: 0.5160
    * **Random Forest: 0.5494**



### 3. SMS Spam Detection
**Objective:** Build a robust classifier to detect spam messages.

* **Preprocessing:** Mapped 'ham' to 0 and 'spam' to 1. Cleaned text data for vectorization.
* **Vectorization:** Used both Count and TF-IDF Vectorizers.
* **Class Imbalance:** Applied **SMOTE** to address the low frequency of spam messages.
* **Models:** Multinomial Naive Bayes.
* **Performance:**
    * Count Vectorized: 0.9726
    * **TF-IDF Vectorized: 0.9859**

---

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Imbalanced-Learn (SMOTE)
* **Tools:** Jupyter Notebook / Google Colab

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/AayushJ91/CODSOFT.git](https://github.com/AayushJ91/CODSOFT.git)

2. Install the required packages:
   ```bash
   pip install scikit-learn pandas numpy imbalanced-learn

3. Navigate to the specific task folder and run the .ipynb or .py files.


Author : https://github.com/AayushJ91
