# Email Spam Detection using Naive Bayes and SVM

## Project Overview

This project is an end-to-end **Email Spam Classifier** built using Natural Language Processing (NLP) and Machine Learning techniques.  
The system classifies emails as **Spam** or **Ham** (legitimate) using TF-IDF vectorization and two classic algorithms:

- Multinomial Naive Bayes
- Support Vector Machine (LinearSVC)

The best performing model is selected based on F1-Score and saved for future use.

---

## Dataset

**Dataset Name:** SpamAssassin Public Corpus  

**Source:**  
[SpamAssassin Email Dataset on Kaggle](https://www.kaggle.com/datasets/bayes2003/emails-for-spam-or-ham-classification-spamassassin)

**Description:**  
This dataset contains labeled emails (Spam and Ham) from the well-known SpamAssassin public mail corpus. It is widely used for training and evaluating spam filters.

**Columns:**
- `label` : 0 = Ham, 1 = Spam
- `text`  : Email content

---

## Project Structure

- Data Loading & Exploration
- Text Cleaning & NLP Preprocessing (Lowercasing, Stopwords Removal, Lemmatization)
- Train-Test Split
- TF-IDF Vectorization (with unigrams + bigrams)
- Model Training (Naive Bayes & SVM)
- Model Evaluation & Comparison
- Error Analysis
- Prediction Function
- Model Saving
