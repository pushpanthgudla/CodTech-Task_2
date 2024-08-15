# CodeTech-Task_2

Name: GUDLA PUSHPANTH

Company: CODETECH IT SOLUTIONS

Id: CT08DS5105

Domain: DATA SCIENCE

Duration: July 15th,2024 to August 15th, 2024

Mentor: Muzammil


## CODTECH-Task2
# Predictive Modeling with Classification

This project involves building predictive models using classification algorithms on a labeled dataset. The goal is to preprocess the data, apply various classification techniques, and evaluate their performance using standard metrics.

## Table of Contents
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
  - [Logistic Regression](#logistic-regression)
  - [Decision Trees](#decision-trees)
  - [Random Forests](#random-forests)
  - [Support Vector Machines](#support-vector-machines)
- [Evaluation Metrics](#evaluation-metrics)
  - [Accuracy](#accuracy)
  - [Precision, Recall, and F1-Score](#precision-recall-and-f1-score)
- [Results](#results)
- [Conclusion](#conclusion)

## Dataset
Provide a brief description of the dataset used, including its source, features, and the target variable. Mention any necessary preprocessing steps taken to clean or transform the data.

## Data Preprocessing
Detail the preprocessing steps such as:
- Handling missing values
- Encoding categorical variables
- Scaling numerical features
- Splitting the data into training and testing sets

## Modeling
### Logistic Regression
- **Description**: A linear model for binary classification.
- **Implementation**: Include details about the library used and any specific parameters.
- **Output Image**: ![Screenshot 2024-07-27 190131](https://github.com/user-attachments/assets/5a6a5354-104a-4e6a-8120-3df1a9115de1)

### Decision Trees
- **Description**: A non-linear model that splits data based on feature values.
- **Implementation**: Include details about the library used and any specific parameters.
- **Output Image**: ![Screenshot 2024-07-27 190138](https://github.com/user-attachments/assets/5f647886-3016-4cf3-b013-362b6a0dfe96)


### Random Forests
- **Description**: An ensemble method using multiple decision trees.
- **Implementation**: Include details about the library used and any specific parameters.
- **Output Image**: ![Screenshot 2024-07-27 190124](https://github.com/user-attachments/assets/b9e4657a-4b33-49b4-a80e-08e38499dca6)


### Support Vector Machines
- **Description**: A classifier that finds the optimal hyperplane for separating classes.
- **Implementation**: Include details about the library used and any specific parameters.
- **Output Image**: ![Screenshot 2024-07-27 190145](https://github.com/user-attachments/assets/0a0b2aab-d9eb-443c-9326-b2f58d47ca92)


## Evaluation Metrics
### Accuracy
![Screenshot 2024-07-27 190153](https://github.com/user-attachments/assets/d700bf07-43a6-4ed5-9a32-6c87eb087741)


### Precision, Recall, and F1-Score
### Classification Metrics

### 1. Precision
The ratio of correctly predicted positive observations to the total predicted positives. Precision is a measure of how many of the predicted positive instances are actually positive.

\[
\text{Precision} = \frac{TP}{TP + FP}
\]

### 2. Recall (Sensitivity)
The ratio of correctly predicted positive observations to all the observations in the actual class. Recall measures how many of the actual positive instances were correctly predicted by the model.

\[
\text{Recall} = \frac{TP}{TP + FN}
\]

### 3. F1-Score
The harmonic mean of precision and recall. It is used to balance the trade-off between precision and recall, especially useful when you have an uneven class distribution.

\[
\text{F1-Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}
\]

## Conclusion
The most suitable algorithm for the given task is given by RANDOM FOREST CLASSIFIER with the accuracy 82.12
