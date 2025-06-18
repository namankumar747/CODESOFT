# CODESOFT

## Movie Genre Classification

This project tackles the multi-label classification problem of predicting movie genres from plot summaries. The dataset contains textual descriptions of movies, which are transformed into numerical features using TF-IDF (Term Frequency–Inverse Document Frequency) vectorization. For classification, a Support Vector Machine (SVM) model is trained to handle the sparse and high-dimensional text features effectively.
The model outputs one or more genres for each movie, such as Action, Comedy, Drama, etc. Evaluation metrics include micro and macro averaged Precision, Recall, and F1-Score, suitable for multi-label classification tasks.
DATASET: https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

## Credit Card Fraud Detection

In this project, the objective is to detect fraudulent credit card transactions from a highly imbalanced dataset. It involves exploring transactional data and applying machine learning models like Logistic Regression, Decision Trees, and Random Forests to classify transactions as either fraudulent or legitimate. Techniques such as resampling, feature scaling, and model evaluation metrics like precision and recall are used to improve accuracy and reduce false negatives, which are critical in fraud detection.

## Spam SMS Detection

This project addresses a binary classification task: detecting whether an incoming SMS message is spam or not. The dataset consists of SMS messages labeled as either "spam" or "ham" (legitimate). The textual data is first preprocessed by converting to lowercase, removing punctuation, and eliminating stopwords.
The cleaned messages are then transformed into numerical form using TF-IDF (Term Frequency–Inverse Document Frequency), which captures the importance of each word relative to the message and the entire corpus.
For classification, a Multinomial Naive Bayes model is employed, which is particularly well-suited for text classification problems with word frequency features. The model is evaluated using standard metrics such as Accuracy, Precision, Recall, and F1-Score, ensuring both high detection rates and minimal false positives.
