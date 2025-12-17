# Precision-First Ensemble Learning for Bank Marketing

## Overview
This project applies ensemble machine learning models to predict which customers are most likely to subscribe to a term deposit, with the goal of optimizing marketing spend.

The key objective is **maximizing precision**, not accuracy.

## Dataset
- Bank Marketing Dataset (Kaggle: https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)
- Binary classification with strong class imbalance

## Approach
- Preprocessing with One-Hot Encoding and class weighting
- Baseline models: Logistic Regression, k-NN
- Ensemble models: Random Forest, AdaBoost, Bagging, Voting
- Probability threshold tuning to align with business costs

## Key Insight
A Random Forest model achieved ~0.80 precision at a higher probability threshold, producing a high-quality customer target list while minimizing wasted outreach.

## Repository Structure
- `notebooks/`: End-to-end modeling notebook
- `data/`: Raw dataset
- `results/`: Key visual outputs

## Medium Article
Full explanation and business context here: [https://medium.com/@apoorva.jishtu/ensemble-learning-in-action-optimizing-bank-marketing-with-precision-first-ml-da3aa3045527?postPublishedType=repub]

