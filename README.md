# Calories-Burnt-Predictor 🔥

A machine learning model built in Python that predicts the number of calories burnt during a workout based on physiological and exercise parameters.

---

## Overview

Given basic details about a person and their workout, this model predicts how many calories they burned. It uses an XGBoost regression algorithm trained on exercise and calorie datasets.

---

## Input Parameters

| Parameter | Description |
|---|---|
| Gender | Male or Female |
| Age | Age in years |
| Height | Height in cm |
| Weight | Weight in kg |
| Duration | Exercise duration in minutes |
| Heart Rate | Heart rate during exercise in bpm |
| Body Temperature | Body temperature in °F |

## Output

> **Predicted Calories Burned** — estimated calories burnt during the workout session

---

## Model Details

| Detail | Value |
|---|---|
| Algorithm | XGBoost Regressor |
| Library | scikit-learn, xgboost |
| Train/Test Split | 80/20 |
| Evaluation Metric | MAE, RMSE (sklearn metrics) |

---

## Project Structure

```
Calories-Burnt-Predictor/
├── calories_burnt_prediction.ipynb   # Main Colab notebook
│
├── dataset/
│   ├── calories.csv
│   └── exercise.csv
│
├── images/
│   └── results.png
│
├── requirements.txt
│
└── README.md
```
## Datasets

The datasets used in this project were sourced from Kaggle.

---

## How To Run

1. Open the notebook in Google Colab
2. Upload `calories.csv` and `exercise.csv` when prompted
3. Run all cells
4. Enter your details when prompted at the end
5. Get your predicted calories burnt


## Tech Stack

- Python
- XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## What I Learned

- Data preprocessing and feature engineering on health datasets
- Correlation analysis using heatmaps
- Training and evaluating an XGBoost regression model
- Taking real user input and generating live predictions
