# student-score-prediction
Machine Learning project to predict students' final scores using attendance, study hours, and previous scores.
# Student Score Prediction

## Project Overview

This project uses Machine Learning to predict students' final scores based on their academic and study-related factors.

The models use:

* Attendance
* Study Hours
* Previous Score

## Machine Learning Models

Two regression models were implemented and evaluated:

* Linear Regression
* Random Forest Regressor

## Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* R² Score

### Results

**Linear Regression**

* MAE: 0.27
* R² Score: 1.00

**Random Forest Regressor**

* MAE: 2.07
* R² Score: 0.97

## Feature Importance

The Random Forest model identified the following feature importance:

| Feature        | Importance |
| -------------- | ---------: |
| Attendance     |      0.367 |
| Study Hours    |      0.323 |
| Previous Score |      0.310 |

## Prediction

The trained model was used to predict a student's final score based on the input features.

**Example Predicted Final Score: 73.4**

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## Project Workflow

1. Load and explore the dataset
2. Perform data preprocessing
3. Select relevant features
4. Train Machine Learning models
5. Evaluate model performance
6. Analyze feature importance
7. Predict the final score

## Files

* `Student_Score_Prediction.ipynb` — Complete Machine Learning implementation
* `requirements.txt` — Required Python libraries
* `README.md` — Project documentation
