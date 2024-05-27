# Diabetes Prediction Models and Analysis

This repository contains a Jupyter notebook for predicting the likelihood of diabetes using various machine learning models. The [dataset](https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes) used includes health-related attributes, and the notebook demonstrates data preprocessing, exploratory data analysis, model development, evaluation, and hyperparameter tuning.

## Features

### Data Loading and Preprocessing
- **Loading the dataset:** Loading the dataset from a CSV file.
- **Handling missing values:** Handling any missing values and scaling the features appropriately.

### Exploratory Data Analysis (EDA)
- **Summary statistics:** Generating summary statistics for the dataset.
- **Data visualization:** Creating visualizations to understand the data distribution and relationships.
- **Correlation analysis:** Analyzing correlations between different features.

### Model Development
- **Logistic Regression:** Implementing and evaluating a Logistic Regression model.
- **Decision Tree:** Implementing and evaluating a Decision Tree model.
- **Random Forest:** Implementing and evaluating a Random Forest model.
- **Model evaluation:** Using accuracy, precision, recall, F1-score, and ROC AUC for model evaluation.

### Hyperparameter Tuning
- **GridSearchCV:** Using GridSearchCV to optimize the hyperparameters of the Random Forest model.
- **Best model evaluation:** Evaluating the best-tuned Random Forest model.

## Dataset

The dataset used in this project includes the following health-related attributes:
- **Id:** Unique identifier for each data entry.
- **Pregnancies:** Number of times pregnant.
- **Glucose:** Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
- **BloodPressure:** Diastolic blood pressure (mm Hg).
- **SkinThickness:** Triceps skinfold thickness (mm).
- **Insulin:** 2-Hour serum insulin (mu U/ml).
- **BMI:** Body mass index (weight in kg / height in m²).
- **DiabetesPedigreeFunction:** Diabetes pedigree function, a genetic score of diabetes.
- **Age:** Age in years.
- **Outcome:** Binary classification indicating the presence (1) or absence (0) of diabetes.

## Results

The best performing model is a Random Forest with the following metrics:
- **Accuracy:** 0.983
- **Precision:** 0.993
- **Recall:** 0.958
- **F1 Score:** 0.975
- **ROC AUC:** 0.977

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, feature requests, or improvements.
