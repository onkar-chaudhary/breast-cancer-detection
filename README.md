# Breast Cancer Detection Project

This project is focused on building a machine learning model to predict the diagnosis of breast cancer (malignant or benign) based on features extracted from the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The final model can be integrated into a web application for user-friendly predictions based on input data.

## Project Overview

Breast cancer is a common health challenge, and early diagnosis is crucial for effective treatment. Using the WDBC dataset, this project applies machine learning techniques to create an accurate model for breast cancer diagnosis.

## Dataset

- **Source**: [Wisconsin Diagnostic Breast Cancer (WDBC) dataset](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**: The dataset contains 30 real-valued features related to cell nuclei characteristics, derived from digitized images of fine needle aspirates of breast masses.
- **Diagnosis**: The target variable, with classes:
  - M (Malignant)
  - B (Benign)

## Features of Interest

Each cell nucleus in the dataset has 10 computed features, each with mean, standard error, and worst values:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

## Project Structure

- `data.csv`: Contains the data files.
- `breast_cancer.ipynb`: Contains Jupyter notebooks for data exploration, preprocessing, and modeling.
- `pipeline_breast_cancer.joblib`: Stores the trained model for deployment.
