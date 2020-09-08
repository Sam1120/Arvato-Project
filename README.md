# Arvato-Project

# 1. Project Overview
In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in 2 phases:

Use Unsupervised Learning to perform customer segmentation and identify clusters/segments from general population who best match mail-order company's customer base.
Use Supervised Learning to identify targets for marketing campaign of the mail-order company who could possibly become their customers.
Goal of this project is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.

# 2. Technical overview:
Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we need to build a preprocessing pipeline to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data, AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

These concepts are covered further in the notebook:

Data Exploration & Cleansing
Dimensionality Reduction
Clustering
Supervised Learning
Final Model Evaluation
Feature Importance
Analysis of identified important features in clusters to find relevance
Scoring and submisstion to Kaggle
