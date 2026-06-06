# Titanic Survival Prediction

Predicting which passengers survived the Titanic disaster
using Machine Learning in Python.

## Problem Statement
The goal is to predict whether a passenger survived (1) or
did not survive (0) based on features like age, sex,
passenger class and fare.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- 891 passengers, 12 original features
- Target column: Survived (0 or 1)

## Project Steps
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Model training — Random Forest Classifier
5. Model evaluation

## Key Findings from EDA
- Women survived at 74% vs men at only 19%
- 1st class: 63% survival, 3rd class: only 24%
- Children had higher survival rates than adults
- Cabin column dropped — 77% missing values
- Age filled using median per passenger class

## Results
| Metric | Score |
|--------|-------|
| Accuracy | ~82% |
| Model | Random Forest (100 trees) |
| Train size | 713 rows |
| Test size | 178 rows |

## Tech Stack
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn, Missingno
- Scikit-learn

## How to Run
1. Open `titanic-survival-prediction.ipynb` in Google Colab
2. Run all cells from top to bottom
3. Dataset loads automatically from URL — no download needed

## What I Learned
- How to perform full EDA before modelling
- How to handle missing values (median vs mean vs mode)
- How to encode categorical variables
- How to evaluate a classification model beyond just accuracy
