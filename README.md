# Titanic Survival Prediction

This repository contains Python code for predicting survival on the Titanic using machine learning algorithms. The dataset includes information about passengers, such as their age, class, and fare. The primary goal is to build a model that can predict whether a passenger survived or not.

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/seyyedmsl82/Titanic_Dataset_prediction.git
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and place the `train.csv` and `test.csv` files in the `input` folder.

## Overview

The code provided covers the following steps:

1. **Understanding Data:** Loading the dataset, displaying the first few rows, and generating summary statistics.
   
2. **Data Cleaning:** Handling missing values in the dataset.

3. **Splitting Data:** Preparing the dataset for training by splitting it into features and labels.

4. **Data Preprocessing:** Encoding categorical variables and scaling numerical features.

5. **Modeling:** Training several machine learning models, including Logistic Regression, K-Nearest Neighbors, Support Vector Machine, CatBoost, and Random Forest.

6. **Model Evaluation:** Assessing the accuracy of each model on the training and testing datasets.

7. **Submission:** Making predictions on the test dataset and generating a submission file.

## Usage

You can run the code using a Jupyter notebook or any Python environment that supports the required libraries. Adjust the file paths and parameters as needed.

Feel free to experiment with different models, hyperparameters, and feature engineering techniques to improve prediction accuracy.
