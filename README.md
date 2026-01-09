# Iris Classification – ML Workflow Enhancement

## Project Overview
This project extends an existing open-source Iris classification repository by
modernizing the machine learning workflow and introducing a metric-driven model
promotion mechanism.

## What Was Implemented
- Reproducible train-test split with stratification
- Logistic Regression baseline model
- Model evaluation using accuracy, F1-score, and confusion matrices
- Candidate KNN model comparison
- Conditional deployment gate based on macro F1-score
- Metric persistence using artifacts (`metrics.json`)

## How to Run
1. Open the notebook in Google Colab
2. Upload the `iris.data` file
3. Run all cells from top to bottom

## Assumptions & Limitations
- The Iris dataset is small and clean
- Simple models were intentionally used to focus on MLOps concepts
- No external model registry was used

## Reflection on Using a Coding Assistant
Using a coding assistant helped speed up development and modernize deprecated
APIs. It was particularly useful for structuring the ML workflow and adding
deployment logic. Manual verification was required to ensure correctness and
best practices.
