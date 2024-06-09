

# Heart Disease Prediction using Logistic Regression

This project aims to predict the presence of heart disease based on various clinical and demographic features using logistic regression. The dataset used for training and testing the model can be found on Kaggle [here](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction).

## Dataset Description

The dataset contains several attributes that can be used to predict the presence of heart disease. Some of the key features include age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, and thallium scan results.

## Model Training

Logistic regression, a commonly used classification algorithm, was employed to build the predictive model. The dataset was preprocessed, including handling missing values, encoding categorical variables, and scaling numerical features as necessary. The logistic regression model was then trained on the processed dataset to predict the likelihood of heart disease based on the input features.

## Usage

1. **Data Preparation**: Before running the model, ensure that the dataset is downloaded and placed in the appropriate directory. Any preprocessing steps required should also be performed.

2. **Model Training**: Execute the provided Python script to train the logistic regression model on the dataset.

3. **Prediction**: Once the model is trained, it can be used to make predictions on new data. Input the relevant features into the trained model to obtain predictions for the presence of heart disease.

## Web Application

The heart disease prediction model has been deployed as a web application using the Streamlit library. Streamlit allows for easy creation of interactive web applications directly from Python scripts. Users can input their demographic and clinical information into the web app, and the model will predict the likelihood of heart disease based on the provided features.

To run the web application locally, ensure that Streamlit is installed in your Python environment. Then, execute the Streamlit command with the path to the Python script containing the web application code.

```bash

