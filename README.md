# Fake News Classification Project

## Overview

This project focuses on Fake News Detection using a combination of Machine Learning (ML), Deep Learning (DL), and Ensemble Learning approaches. It aims to combat misinformation by leveraging the WELFake dataset, which aggregates multiple smaller datasets to enhance robustness and generalization.

## Dataset

The project uses the WELFake Dataset containing 72,134 news articles (35,028 real and 37,106 fake). It has the following columns: Serial Numbers, Title, Text Body, Label (0 = Fake, 1 = Real).

Link to dataset: https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification

## Methods and Results

After performing Exploratory Data Analysis (EDA), pre-processing techniques were implmented which included removing unnecessary information(null values, special characters, numbers, URLs), tokeinzation, lemmatization, and more. Term Frequency-Inverse Document Frequency (TF-IDF), a feature engineering technique, commonly used for NLP tasks was also implemented. Following this, we implemented some Machine Learning algorithms(Logistic Regression, SVM, Random Forest, XGBoost), Deep Learning models like Bi-LSTM and BERT, and ensemble learning.

The following image shows the results that were obtained:

![Accuracy and loss values of all the models on test set](images/result.png)


More detailed information with visualizations can be found in the pdf file in this repository.
