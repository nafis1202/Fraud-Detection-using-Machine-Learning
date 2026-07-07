# Fraud Detection System

## About

This project uses machine learning to detect fraudulent financial transactions. I trained the model on a Kaggle dataset containing over 6.3 million transactions and achieved 94% accuracy.

The goal of this project was to build an end-to-end machine learning pipeline, from data preprocessing and feature engineering to model training, evaluation and deployment with Streamlit.

## What I Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Streamlit
* Joblib

## Dataset

The dataset was sourced from Kaggle and contains over 6.3 million financial transactions.

Transaction types included:

* CASH_IN
* CASH_OUT
* PAYMENT
* TRANSFER

## Features

* Cleaned and preprocessed the data
* Performed feature engineering
* Built and trained a machine learning model
* Achieved 94% prediction accuracy
* Saved the model as a reusable Scikit-learn pipeline
* Built a simple Streamlit app for real-time fraud prediction

## Project Structure

```text
Fraud-Detection/
├── fraud_detection.py
├── fraud_detection_pipeline.pkl
├── requirements.txt
├── README.md
└── data/
```

## Future Improvements

* Try additional models such as XGBoost or LightGBM
* Tune hyperparameters to improve performance
* Deploy the application online
* Add more features to improve fraud detection accuracy

