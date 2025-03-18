# Newspaper Classification Using Machine Learning

## Overview
This project implements **text classification** to categorize newspaper articles into predefined labels using **supervised machine learning algorithms**. The model is trained on a dataset of news articles and predicts the category of a given text based on its content.

## Features
- Data preprocessing (removal of stop words, punctuation, and vectorization using TF-IDF/Word2Vec)
- Supervised Machine Learning models: **SVM, Naive Bayes, Logistic Regression**
- Performance evaluation with accuracy metrics
- Comparisons with research literature

## Dataset
- **Source:** [GitHub - BBC News Dataset](https://github.com/DiveshRKubal/Data-Science-Use-Cases/blob/master/News%20Classification/BBC%20News.csv)
- **Size:** 1491 rows × 3 columns
- **Columns:** `ArticleID`, `Category`, `Text`
- Data preprocessing includes handling null values and preparing text for model training

## Implementation
### Data Collection & Preprocessing
- Remove null values
- Tokenization and stop-word removal
- Convert textual data to numerical format using **TF-IDF** and **Word2Vec**

### Model Training & Testing
- **Algorithms used:**
  - **Support Vector Machine (SVM)**
  - **Naive Bayes**
  - **Logistic Regression**
- Training performed using **Scikit-Learn**
- **Accuracy comparison** shows **SVM achieved the highest accuracy (94%)**

## Results
- The **SVM model** provided the best accuracy among the tested models.
- Accuracy comparison with reference research paper (**88% accuracy for SVM**) confirms the model's performance.

## Applications
- **Spam filtration**
- **Educational content tagging**
- **Sentiment analysis**
- **News categorization**

## Future Work
- Experimenting with **Neural Networks and Transformer models (e.g., BERT, DistilBERT)**
- Exploring relationships among sentences for better classification
- Expanding the study into a research article by testing on various datasets
