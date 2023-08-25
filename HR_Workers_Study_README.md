
# HR Workers Study: Understanding Employee Attrition

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Model Building](#model-building)
6. [Model Evaluation](#model-evaluation)
7. [Conclusion and Interpretation](#conclusion-and-interpretation)
8. [Requirements](#requirements)
9. [Usage](#usage)

## Introduction
This project aims to understand the reasons behind employee attrition and suggests actionable insights for the company to reduce it.

## Dataset
The dataset used is 'WA_Fn-UseC_-HR-Employee-Attrition.csv', which contains various features related to employees, such as 'Age', 'DistanceFromHome', 'YearsSinceLastPromotion', etc.

## Data Preprocessing
- Checked for missing values.
- Created a new feature 'AgeGroup' based on the 'Age' feature.

## Exploratory Data Analysis
Various visualizations were made to understand the data better. For example, a countplot was generated to visualize the distribution of 'AgeGroup' concerning 'Attrition'.

## Model Building
Various machine learning models were used to predict attrition based on employee features.

## Model Evaluation
The models were evaluated based on metrics like F1-score and recall. SMOTE was used to balance the classes.

## Conclusion and Interpretation
- Younger employees and those living farther from the office are more likely to leave.
- 'YearsSinceLastPromotion' is a significant feature affecting attrition.

## Requirements
A `requirements.txt` file is included for setting up the environment.

## Usage
1. Clone the repository.
2. Install the requirements using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook.

