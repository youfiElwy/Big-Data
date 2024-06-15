# Assignment 3 Overview

This assignment contains a variety of tasks involving different datasets and machine learning techniques. Below is a detailed summary of the tasks:

## Tasks

### Task 1: Age and Salary Analysis
- **Dataset:** The `age_salary_hours` dataset provides key information about individuals’ demographics and employment status.
  - **Columns:**
    - `Age`: Represents the age of individuals.
    - `Annual Salary`: Indicates the annual salary of individuals.
    - `Weekly Hours`: Denotes the number of weekly working hours of individuals.
    - `Education`: Represents the education level of individuals.
- **Objective:** Using SparkSQL, determine the 5 age groups with the highest average annual salary.

### Task 2: Gender Classification
- **Dataset:** The dataset includes various physical features of individuals.
  - **Columns:**
    - `long_hair`: Indicates whether the person has long hair (1 for yes, 0 for no).
    - `forehead_width_cm`: Width of the forehead from right to left in cm.
    - `forehead_height_cm`: Height of the forehead from where the hair grows to the eyebrows in cm.
    - `nose_wide`: Indicates if the nose is wide (1 for yes, 0 for no).
    - `nose_long`: Indicates if the nose is long (1 for yes, 0 for no).
    - `lips_thin`: Indicates if the person has thin lips (1 for yes, 0 for no).
    - `distance_nose_to_lip_long`: Indicates if the distance from nose to lip is long (1 for yes, 0 for no).
    - `gender`: Gender of the individual (1 for Male, 0 for Female).
- **Objective:** Use the DecisionTreeClassifier in SparkML to classify individuals as male or female based on their physical features. Perform any necessary featurization before applying the classifier and calculate the accuracy.

### Task 3: Income Prediction with Decision Trees
- **Dataset:** This dataset contains various demographic and employment features of individuals.
  - **Columns:**
    - `Age`: Represents the age of individuals.
    - `workclass`: Specifies the type of workclass the individual belongs to.
    - `fnlwgt`: Denotes the final weight of the individual.
    - `Education`: Represents the education level of individuals.
    - `educational-num`: Denotes the educational number assigned to the individual.
    - `marital-status`: Specifies the marital status of the individual.
    - `occupation`: Represents the occupation.
    - `relationship`: Specifies the relationship status.
    - `race`: Race of the individual.
    - `Gender`: Gender of the individual.
    - `capital-gain`: Represents the capital gain of the individual.
    - `capital-loss`: Denotes the capital loss of the individual.
    - `hours-per-week`: Specifies the number of hours per week the individual works.
    - `native-country`: Represents the native country of the individual.
    - `income`: Specifies the income level (0 for <=50K, 1 for >50K).
- **Objective:** Utilize the DecisionTreeClassifier in SparkML to predict individuals' income levels. Perform any necessary featurization before applying the classifier and calculate the accuracy.

### Task 4: Income Prediction with Logistic Regression
- **Dataset:** Same as Task 3.
- **Objective:** Use LogisticRegression in SparkML to:
  1. Find the average weekly hours worked by individuals grouped by gender.
  2. Predict income levels based on various features. Perform any necessary featurization before applying the classifier and calculate the accuracy.

### Task 5: Email Spam Classification
- **Dataset:** The dataset includes various features extracted from email contents.
  - **Columns:**
    - `Email No.`: String representing the number of email (index).
    - `Spam`: Indicator if the email is spam (1 if spam, 0 if not).
    - The other 28 columns are integers representing the number of occurrences of each word in the email.
- **Objective:** Use the RandomForestClassifier in SparkML to classify emails as spam or non-spam based on the occurrence of certain words. Perform any necessary featurization before applying the classifier and calculate the accuracy.
