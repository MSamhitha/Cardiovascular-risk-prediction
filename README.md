# Cardiovascular-risk-prediction
This project aims to predict the ten-year risk of coronary heart disease (CHD) by leveraging machine learning models and exploratory data analysis (EDA).
## Dataset Info

The dataset used in this project contains the following columns:

- **id**: Represents a unique identifier for each individual in the dataset.
- **age**: Age of the individual in years.
- **education**: Education level, encoded categorically or numerically.
- **sex**: Biological sex of the individual (0 for female, 1 for male).
- **is_smoking**: Smoking status (0 for non-smoker, 1 for smoker).
- **cigsPerDay**: Number of cigarettes smoked per day.
- **BPMeds**: Blood pressure medication usage (0 for not taking medication, 1 for taking medication).
- **prevalentStroke**: History of stroke (0 for no stroke history, 1 for stroke history).
- **prevalentHyp**: Prevalent hypertension (0 for no hypertension, 1 for hypertension).
- **diabetes**: Diabetes status (0 for no diabetes, 1 for diabetes).
- **totChol**: Total cholesterol level in mg/dL (milligrams per deciliter).
- **sysBP**: Systolic blood pressure in mmHg (millimeters of mercury).
- **diaBP**: Diastolic blood pressure in mmHg.
- **BMI**: Body mass index.
- **heartRate**: Resting heart rate in beats per minute.
- **glucose**: Blood glucose level in mg/dL.
- **TenYearCHD**: Presence or absence of the ten-year risk of developing coronary heart disease (CHD) (0 for no risk, 1 for risk).
- 
## Data Exploration
- Explored the dataset through visualizations to gain insights into the factors contributing to CHD risk.
- Identified correlations between features and CHD risk.
- Detected outliers and anomalies in the data.

- ## Machine Learning Models

In this project, various machine learning models were implemented to predict CHD risk, including Logistic Regression, Random Forest, and Naive Bayes. Cross-validation and hyperparameter tuning were performed to optimize the model performance.

Here is the evaluation table for the models:

| Model                            | Accuracy | Precision | Recall  | F1 Score |
|----------------------------------|----------|-----------|---------|----------|
| Logistic Regression              | 0.672743 | 0.658163  | 0.687389| 0.672459 |
| Logistic Regression with Grid Search | 0.678819 | 0.664957  | 0.690941| 0.677700 |
| **Random Forest**                    | **0.897569** |**0.895204** | **0.895204**| **0.895204** |
| Random Forest with Randomized Search | 0.885417 | 0.880071  | 0.886323| 0.883186 |
| Naive Bayes                      | 0.644097 | 0.637343  | 0.630551| 0.633929 |
| Naive Bayes with Grid Search     | 0.644097 | 0.637343  | 0.630551| 0.633929 |

These models were assessed based on accuracy, precision, recall, and F1 Score to determine their performance in predicting CHD risk.

The Random Forest model, with an accuracy of 0.897569 and balanced precision, recall, and F1 Score, is recommended for CHD risk assessment.

