# TripAdvisor Hotel Reviews Sentiment Analysis

This project performs sentiment analysis on TripAdvisor hotel reviews using a logistic regression model. It classifies the sentiment of each review (positive, negative, or neutral) based on the reviewer's rating.

## Overview

This repository includes Python scripts for:

* **Data preprocessing:** Cleaning and transforming raw text data for model training.
* **Model training:** Training a logistic regression model using scikit-learn on the preprocessed data.
* **Model evaluation:** Evaluating the trained model's performance using accuracy score.
* **Prediction:** Predicting the sentiment of new hotel reviews based on the trained model.

## Requirements

* Python 3
* Pandas
* NumPy
* scikit-learn
* `re` (regular expression) module

## Dataset

The project uses the TripAdvisor Hotel Reviews dataset, containing hotel reviews and corresponding ratings. Each review has a sentiment label based on the reviewer's rating.
