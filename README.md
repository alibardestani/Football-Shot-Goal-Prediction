# Football Shot Goal Prediction

This project aims to predict the probability of football shots resulting in goals using machine learning techniques. The analysis is based on a dataset derived from the Shahin team's match statistics.

## Table of Contents
- [Introduction](#introduction)
- [Problem Objective](#problem-objective)
- [Data Preprocessing](#data-preprocessing)
- [Feature Selection](#feature-selection)
- [Model Development](#model-development)
- [Technologies Used](#technologies-used)

## Introduction
Data analysis in football is essential for teams aiming to improve their performance. By utilizing advanced analytical techniques, this project explores the key factors that influence shot outcomes in football matches.

## Problem Objective
The main goal of this project is to predict the likelihood of each shot resulting in a goal. We will perform necessary preprocessing steps and focus on feature selection to identify the most significant variables affecting shot outcomes.

## Data Preprocessing
The dataset is preprocessed by:
- Cleaning and transforming data.
- Creating new features like shot distance and angle.
- Handling missing values.

## Feature Selection
We use various feature selection methods to identify the most impactful features that contribute to predicting shot outcomes, ultimately improving model performance.

## Model Development
An automated machine learning model is built using FLAML's AutoML framework. The project compares the performance of models trained on raw data versus preprocessed data, evaluating accuracy through metrics like ROC AUC scores.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- FLAML
- Matplotlib (for visualization)
