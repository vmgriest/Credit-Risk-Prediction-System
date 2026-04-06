# Credit Risk Prediction System

A web application that compares multiple machine learning models to classify credit records as **high risk** or **low risk**. Upload credit data and see which model performs best.

## Models Compared

- Linear Discriminant Analysis (LDA)
- Logistic Regression
- Naive Bayes
- k-Nearest Neighbors (k=5)

## Features

- Upload CSV credit data for instant classification
- Side-by-side model comparison
- Performance visualization
- Clean Flask web interface

## Technologies Used

- Python
- Flask
- scikit-learn
- JavaScript
- HTML/CSS
- Pandas

## Dataset

Uses credit risk data from the [UnivAI Hackathon dataset on Kaggle](https://www.kaggle.com/datasets/arunavgautam/credit-risk-prediction-by-univai-hackathon).

## Installation

```bash
git clone https://github.com/vmgriest/Credit-Risk-Prediction-System.git
cd Credit-Risk-Prediction-System
pip install -r requirements.txt
python app.py
