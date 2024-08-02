# Predicting-AirBnB-Rates

This repository contains a Jupyter Notebook that uses machine learning and deep learning to predict the nightly rates of properties in Bristol, with the overall aim of minimizing error in predictions.  

## Table of Contents

- Introduction
- Dataset
- Notebook Contents
- Conclusions
- Contributing

## Introduction

This project showcases several techniques and tools used for data analysis and machine learning. This notebook showcases how to preprocess data, explatory data analysis, and apply machine learning models. 

## Dataset

The dataset is sourced from InsideAirbnb.com and contains information on 6,700 AirBnB listings in Bristol. A variety of data types exist in the dataset, which are explained in detail within the notebook. 

## Notebook Contents

The notebook is structured as follows:

1. **Data Loading and Preparation:** Importing libraries, loading datasets and preparing the data for subsequent analysis.
2. **Data Analysis:** Performing explatory data analysis to understand the dataset.
3. **Data Cleaning:** Handling missing values, encoding categorical variables and transforming data.
4.  **Visualization:** Creating plots and visualizations to illustrate data insights.
5.   **Machine Learning:** Implementing machine learning models to make predictions and evaluate performance.

## Conclusions

After experimenting with various machine learning and deep learning models, the best performing model was a four-layered neural network, with L1 regularization and an Adam optimizer. This model achieved an MSE of 0.1322 and an r^2 of 0.6872 on the validation dataset. 

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.

