## Diabetes Prediction Models and Analysis

This repository contains a Jupyter notebook for predicting the likelihood of diabetes using various machine learning models. The dataset used includes health-related attributes, and the notebook demonstrates data preprocessing, exploratory data analysis, model development, evaluation, and hyperparameter tuning.

## Features

- **Data Loading and Preprocessing:**
  - Loading the dataset from a CSV file.
  - Handling missing values and feature scaling.
  
- **Exploratory Data Analysis (EDA):**
  - Summary statistics and data visualization.
  - Correlation analysis and distribution plots.

- **Model Development:**
  - Implementation of Logistic Regression, Decision Tree, and Random Forest models.
  - Model training and evaluation using accuracy, precision, recall, F1-score, and ROC AUC.

- **Hyperparameter Tuning:**
  - Using GridSearchCV to optimize the hyperparameters of the Random Forest model.
  - Evaluation of the best-tuned model.

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

## License

This project is licensed under the MIT License. See the \`LICENSE\` file for more details." >> README.md
