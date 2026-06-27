# Student Performance Prediction

## Project Overview

This project was completed as part of my Data Science Internship at InternVision Tech.

The objective of this project is to develop and evaluate machine learning models that predict student academic performance based on study-related factors.

---

## Dataset

The dataset contains approximately **1,000,000 student records** with the following attributes:

* Student ID
* Weekly Self Study Hours
* Attendance Percentage
* Class Participation
* Total Score
* Grade

The target variable used for prediction is **Total Score**.

---

## Project Workflow

### Data Collection

* Loaded the dataset using Pandas.

### Data Preprocessing

* Checked missing values.
* Verified data types.
* Confirmed that no encoding was required.
* Selected relevant input features.
* Split the dataset into training and testing sets.

### Exploratory Data Analysis

* Distribution of Total Score
* Study Hours vs Total Score
* Attendance vs Total Score
* Class Participation vs Total Score
* Correlation Heatmap

### Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Model Performance

| Model             |      MAE |  RMSE |   R² Score |
| ----------------- | -------: | ----: | ---------: |
| Linear Regression |     7.16 |  9.00 | **0.6600** |
| Decision Tree     |     8.37 | 11.63 |     0.4319 |
| Random Forest     | **6.68** |  9.06 |     0.6549 |

Linear Regression achieved the highest R² Score, while Random Forest produced the lowest Mean Absolute Error.

---

## Visualizations

* Correlation Heatmap
* Model Comparison
* Feature Importance
* Actual vs Predicted Values



## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Conclusion

Three machine learning models were developed and compared to predict student performance.

Linear Regression achieved the highest R² Score (0.6600), while Random Forest produced the lowest prediction error (MAE = 6.68). The project demonstrated the complete machine learning workflow, including preprocessing, exploratory analysis, model development, evaluation, and interpretation.

---

## Author

**Nazerke Supotayeva**

Data Science Intern

GitHub: https://github.com/Nazzekax

