# Fake Job Posting Detection Using Machine Learning

## Overview

This project uses machine learning and natural language processing to detect fraudulent job postings. The goal was to classify job listings as genuine or fraudulent using job descriptions, company details, and structured posting information.

## Problem

Online job scams can put job seekers at risk of identity theft, financial loss, and wasted time. This project explores how classification models can help identify suspicious job postings before they reach applicants.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLP
- TF-IDF
- Logistic Regression
- Naive Bayes
- Random Forest
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

- Cleaned and preprocessed text and structured job posting data
- Handled missing values and class imbalance
- Converted text fields into numerical features using TF-IDF
- Trained and compared multiple classification models
- Evaluated model performance using precision, recall, F1-score, and ROC-AUC

## Models Used

- Logistic Regression
- Naive Bayes
- Random Forest
- XGBoost

## Key Findings

- Fraudulent postings were more likely to have missing company profiles.
- Remote job postings showed a higher fraud rate than non-remote postings.
- Fake postings often used vague or enticing language such as work-from-home or data-entry terms.
- XGBoost provided the strongest overall performance.
- Accuracy alone was not enough because the dataset was highly imbalanced.

## Business Impact

This project shows how machine learning can help job platforms detect suspicious postings, reduce scam exposure, and protect job seekers. Because false positives and false negatives can have real consequences, the model should be used as a decision-support tool with human review.

## Full Report

For complete visualizations, detailed analysis, model evaluation, storytelling, and ethical considerations, view the full report:

📄 `fake_job_detection_report.pdf`

## Dataset Reference

Kaggle Dataset: Real or Fake? Fake Job Posting Prediction  
https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction

---

⭐ Thank you for viewing this project.
