# Phishing-Website-Detection
A machine learning project for detecting phishing websites using multiple classifiers and SMOTE for class balancing.

# Goal
The primary goal of this project is to develop a binary classification model that can distinguish between legitimate and phishing websites based on their features. By experimenting with various machine learning algorithms, this project evaluates the performance of different classifiers to find the most effective model for detecting phishing websites.

# Dataset Information
* Dataset Name: Phishing Website Detection Dataset
* Size: 11,055 entries, 32 features
* Classes: Legitimate (0) and Phishing (1)
* Data Type: Integer values across all features
* Feature Values: Primarily -1, 0, and 1
  
Note: The dataset features that need preprocessing.
The dataset is divided into input features (X) and a target variable (y). Class balancing techniques, such as SMOTE, were applied to address the class imbalance present in the dataset.

# Exploratory Data Analysis (EDA) & Preprocessing
Data Cleaning:
Target values were standardized by converting -1 to 0 to create binary labels.
Feature Engineering:
Outliers were analyzed and potentially removed.
Important features were identified and retained for modeling.
Data Balancing:
SMOTE (Synthetic Minority Over-sampling Technique) was applied to address class imbalance.
Train-Test Split:
Data was split into training and testing sets to evaluate the model's performance on unseen data.

# Models
Several machine learning models were trained and evaluated to identify the best-performing classifier:

* Random Forest Classifier
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Naive Bayes Classifier
Each model was evaluated using cross-validation to ensure robust and reliable results. Model evaluation metrics include accuracy, precision, recall, and F1-score to understand the strengths and limitations of each approach.

# Results
Model performances were summarized in a results table that includes mean accuracy and standard deviation across multiple folds of cross-validation.

Key metrics are:

Accuracy: Indicates the overall correctness of predictions.
Precision and Recall: Evaluate the model’s ability to correctly identify phishing websites.
F1-score: A balanced measure of precision and recall.

# Conclusion
This project demonstrates the potential of machine learning models in detecting phishing websites. The comparative analysis across various algorithms revealed the strengths of certain models over others. Based on accuracy and other metrics, [Best Model] emerged as the best-performing model, providing a reliable approach to identifying phishing sites.
