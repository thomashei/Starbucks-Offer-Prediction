# Predicting Customer Responses with Machine Learning - Starbucks Offers Showcase

This repository contains the code and resources for the project "Predicting Customer Responses with Machine Learning," which serves as a showcase of predicting customer responses to mobile app offers using Starbucks offer data.

## Project Overview

The project focuses on analyzing the impact of different attributes of members and offers on the likelihood of a customer's response to an offer. The aim is to optimize mobile app offers based on customer profiles. The analysis and modeling process include:

1. Preprocessing the dataset to handle missing values, categorical variables, and feature engineering.
2. Building and training an XGBoost classifier to predict customer responses to offers.
3. Evaluating the model's performance using accuracy and classification metrics.
4. Exploring feature importance to understand the key factors influencing customer responses.
5. Predicting members responses with a new randomly created offer set.

The findings and insights derived from this project can be applied by businesses to enhance their targeting strategies and improve the effectiveness of their offers.

## Repository Structure

- `data/`: This directory contains the raw and preprocessed datasets used in the project.
- `notebook/`: Jupyter notebooks that walk through the data preprocessing, modeling, and analysis steps.
- `model/`: Saved model file for future use or deployment.
- `README.md`: This file, providing an overview and instructions for the project.

## Dependencies

The project uses Python 3 and the following libraries:
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn

Install the necessary dependencies using pip:


## Acknowledgments

This project was completed as part of the Udacity Data Scientist Nanodegree Program. We would like to thank Udacity and Starbucks for providing the dataset and guidance throughout the project.

## Contact

For any questions or inquiries, please contact [Thomas Ying](mailto:thomashei0828@gmail.com).

## Blog Post

For detailed information about the project and its findings, please refer to the accompanying [essay]([https://medium.com/@thomashei0828/predicting-customer-responses-with-machine-learning-starbucks-offers-as-showcase-fe9016fa19d3])
