# Instructor Effectiveness Modeling — EdTech Platform

## Overview
This project analyzes instructor effectiveness across multiple course batches 
on an EdTech platform using learner outcome, engagement, and feedback data.
A composite effectiveness score is defined and a machine learning model is 
built to classify instructors into Low, Medium, and High effectiveness tiers.

## Problem Statement
To classify instructor effectiveness across multiple course batches by defining 
a weighted effectiveness score from learner metrics and predicting an instructor's 
effectiveness tier (Low / Medium / High) using machine learning.

## Dataset
- 2000 batch-level records across 120 instructors and 25 courses
- Features: completion rate, score improvement, quiz scores, 
  watch time, assignment submissions, forum activity, feedback scores

## Approach
1. Exploratory Data Analysis (EDA)
2. Feature Engineering — Weighted Effectiveness Score
3. Batch → Instructor Level Aggregation
4. Model Building — Logistic Regression
5. Model Evaluation — Accuracy, Classification Report, Confusion Matrix
6. Feature Importance & Interpretation

## Results
- Test Accuracy: 75%
- CV Accuracy: 73.3% ± 9%
- completion_rate and avg_score_improvement were the strongest predictors

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Submission
Assignment submitted as part of Accredian Data Science Internship selection.
