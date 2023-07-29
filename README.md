# Overview

This repository contains a Fake News Detection Machine Learning Prediction Model. The model is designed to classify news articles 
as either "Fake News" or "Not Fake News" (i.e., legitimate news) based on their features and metadata.

# Dataset

The model is trained on a labeled dataset of news articles. The dataset includes various features of each article, such as the 
source, publication date, number of reviews, review scores, etc. The target variable is binary, 
with 0 representing "Fake News" and 1 representing "Not Fake News."

Dataset - https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets

# Model Architecture

The model utilizes a combination of machine learning algorithms to classify the news articles. The key steps in the model pipeline 
include:

**Data Preprocessing:** The dataset is preprocessed to handle missing values and remove irrelevant features that do not contribute 
significantly to the prediction task.

**Feature Engineering:** Additional features may be engineered from the existing data to provide more information for the classification 
models. For example, one can derive features like the number of reviews per day or sentiment scores from the text data.

**Model Training:** The preprocessed dataset with engineered features is used to train several machine learning models, including 
Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest. The models are trained on a labeled training dataset.

**Model Evaluation:** The trained models are evaluated on a separate test dataset to measure their performance. Evaluation metrics such 
as accuracy, precision, recall, and F1-score are computed to assess model effectiveness.

**Prediction:** The best-performing model is then used to predict the class labels (Fake News or Not Fake News) for new, unseen news articles.

# Requirements

To run the prediction model, you'll need the following dependencies:

Python 3
pandas
numpy
sklearn

# Acknowledgments

This project is inspired by the challenge of detecting fake news and contributes to the field of Machine Learning.



### Note : This project can be extend to stock market prediction , which will be using in coming days...
