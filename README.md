# Breast Cancer Classification using Random Forest

## Project Overview

This project uses Machine Learning to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer Wisconsin dataset provided by Scikit-learn.

A **Random Forest Classifier** is used to train the model and make predictions based on different characteristics of the tumors.

## Dataset

The project uses the built-in Breast Cancer Wisconsin dataset from Scikit-learn.

The dataset contains:

- 569 samples
- 30 features
- 2 target classes

The target classes are:

- 0: Malignant
- 1: Benign

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Google Colab

## Machine Learning Model

The project uses a **Random Forest Classifier**.

Random Forest combines multiple Decision Trees to improve prediction performance and reduce the risk of overfitting.

## Data Splitting

The dataset was divided into:

- 80% Training Data
- 10% Testing Data
- 10% Validation Data

The data was split using `train_test_split` with stratification to maintain the class distribution.

## Project Workflow

1. Load the Breast Cancer dataset.
2. Convert the dataset into a Pandas DataFrame.
3. Separate the target class from the features.
4. Split the data into training, testing, and validation sets.
5. Train the Random Forest model.
6. Make predictions on the test data.
7. Calculate prediction probabilities.
8. Evaluate the model using classification metrics and a confusion matrix.

## Files

- `Breast_Cancer_Classification.ipynb` - Main Google Colab notebook containing the data preparation, model training, predictions, and evaluation.

## How to Run

The notebook can be opened and run using Google Colab or Jupyter Notebook.

