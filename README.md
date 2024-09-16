# NLP-project
# Duplicate Question Classifier
This project implements a duplicate question classifier for Quora using Natural Language Processing (NLP) techniques. The goal is to predict whether two questions are semantically equivalent (duplicates) based on textual features and advanced NLP methods.

# Key Features:

# Data Preprocessing:
  Loaded Quora Question Pairs dataset containing pairs of questions and their duplicate labels.
  Applied text cleaning techniques:
  Lowercasing.
  Removing special characters using regex.
  Stripping HTML using BeautifulSoup.
  Removing stopwords and punctuation.
  
# Feature Engineering:
  Bag of Words (BoW): Converted the questions into vector form using the BoW approach to analyze word frequency.
  TF-IDF (Term Frequency-Inverse Document Frequency): Weighed the importance of words across all questions.
  
# Advanced Features:
  Added word-level features like common word counts between questions.
  Calculated Jaccard similarity to measure set similarity between question pairs.
  
# Exploratory Data Analysis (EDA):
  Visualized the data distribution to understand the nature of duplicates and non-duplicates.
  Displayed the pairwise relationships between features like word overlap and text length.
  
# Model Building:
  Implemented and tested various machine learning models:
  Logistic Regression.
  Support Vector Machines (SVM).
  Random Forests.
  Used performance metrics like Accuracy, F1-Score, and ROC-AUC to evaluate the models.
  
# Evaluation & Results
  Compared models and selected the best-performing model for final classification.
  Displayed key insights about the feature importance for the final model.


The link for Dataset is given below:
https://www.kaggle.com/c/quora-question-pairs

