# Phishing URL Detection Using Machine Learning

## Abstract
The conflict of having to become safer on the
internet is one. continually expanding one, and phishing attacks
are a huge part of concern. As for the current work, several
aspects of supervised learning are explored in the present paper.
Decision Tree and others are generally very handy when it
comes to detecting phishing links. RF has been developed in
computer science along with Support Vector Machine (SVM),
Naive Bayes, k-nearest Neighbors (KNN), and linear support
vector classifier. (LSVC). The validity of each model is then
discussed and as well their strength and possible weaknesses as in
identifying These factors are used especially, targets of phishing
attempts are highlighted. So to improve the results further, we
recommend an ensemble of three classifiers – Random Forest,
Logistic Regression, and Gradient Boost, the top three models.
It is an ensemble technique that uses predictions of several
base estimators to enhance the sorte of generality or stability
compared to another estima to or, for a model compared to
the others or compared to a multivariat The study also reveals
that ensemble design strategies enhance the performance of the
systems. and as such enhance the current phishing detection
systems with better defenses against such attacks. Therefore,
the results of this research will improve the advance. measures
related to security and greatly stress the advisability of using
various methods existing and in use in the contemporary currents
of cyber security

## Datasets
### 1. [Phishing and Legitimate URLs Dataset](https://www.kaggle.com/datasets/harisudhan411/phishing-and-legitimate-urls)
- **Source:** Kaggle
- **Description:** This dataset contains a collection of phishing and legitimate URLs, labeled for supervised learning tasks.
- **Features:**
  - 88,647 phishing URLs
  - 48,932 legitimate URLs
  - 9 Features including URL length, domain registration, and more.

### 2. [PhishDataset](https://github.com/ESDAUNG/PhishDataset)
- **Source:** GitHub
- **Description:** Another comprehensive dataset consisting of phishing and legitimate URLs with a diverse range of features.
- **Features:**
  - 27,000 phishing URLs
  - 35,000 legitimate URLs
  - Features such as domain age, the presence of suspicious characters, and domain-based attributes.

## Project Objectives
- **Preprocess the data:** Clean and preprocess the datasets to remove null values and perform feature engineering.
- **Feature extraction:** Extract relevant features from the URLs such as length, number of dots, special characters, and domain age.
- **Modeling:** Implement various machine learning models like Decision Trees, Random Forests, SVM, Naive Bayes, KNN, LSVC and Proposed Technique (Ensemble technique of Logistic Regression, Random Forest and Gradient Boosting) to classify the URLs as either phishing or legitimate.
- **Evaluation:** Evaluate model performance based on accuracy, precision, recall, F1-score, and ROC curve.

