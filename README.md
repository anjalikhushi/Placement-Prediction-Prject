# Job-Placement-Prediction-Model
![download](https://github.com/anjalikhushi/Placement-Prediction-Project/assets/82653640/4201d75f-c992-4de1-b9f8-9a690a702855)

## Introduction:

The primary objective of a job placement prediction model is to predict the likelihood of a candidate getting placed in a job. This prediction helps educational institutions, recruitment agencies, and companies streamline their hiring process by focusing on candidates with higher probabilities of placement.

## Data Preparation:

Raw data collected needs to be cleaned and preprocessed to ensure accuracy. This involves:

Handling missing values: Filling in or removing incomplete data.

Normalization: Scaling features to ensure uniformity.

Encoding categorical variables: Converting non-numeric data into numeric form.

Feature selection: Identifying and using the most significant factors that influence job placement.


## Exploratory Data Analysis:

EDA is the process of analyzing data sets to summarize their main characteristics, often using visual methods. This helps in understanding the data distribution, identifying anomalies, and forming hypotheses about the data.

Example EDA Tasks:

Plotting the distribution of GPA scores.

Analyzing the correlation between work experience and job placement.

Visualizing the distribution of placements across different academic departments.

## Feature Engineering:

Feature Engineering involves creating new features from the existing data to improve the predictive power of the model.

Steps in Feature Engineering:

Handling Categorical Variables:

Label Encoding: Convert categorical variables into numerical format (e.g., male/female to 0/1).

One-Hot Encoding: Create binary columns for each category.

Scaling and Normalization:

Standardization: Transform features to have zero mean and unit variance.

Min-Max Scaling: Scale features to a specific range (e.g., 0 to 1).


## Machine Learning Model:

Choosing the right algorithm is crucial for prediction accuracy.

Logistic Regression: For binary classification (placed or not placed).



# About Data:
1.gender: Gender of the applicant

2.ssc_percentage: Percentage of marks obtained in 10th grade (SSC)

3.ssc_board: Board of education for 10th grade (SSC)

4.hsc_percentage: Percentage of marks obtained in 12th grade (HSC)

5.hsc_board: Board of education for 12th grade (HSC)

6.hsc_subject: Field of study in 12th grade (HSC)

7.degree_percentage: Percentage of marks obtained in undergraduate degree

8.undergrad_degree: Field of study in undergraduate degree

9.work_experience: Whether the applicant has work experience or not

10.emp_test_percentage: Percentage of marks obtained in the employment test
11.specialisation: Specialization chosen in MBA
12.mba_percent: Percentage of marks obtained in MBA
13.status: Whether the applicant was placed or not

## How to Perform:

To perform a machine learning project using this dataset, you could explore the relationships between various features and the "status" column. This could involve analyzing which factors have a significant impact on whether an applicant is placed in a job or not. Based on this analysis, you could build a machine learning model to predict the placement status of future job applicants given their educational background and other relevant factors. The analysis and design of such a project would involve data preprocessing, exploratory data analysis, feature engineering, model selection, and evaluation.
