# Predicting Job Placement: A Comparative Analysis of GPA and Institution Name
## Karen Yuan & Mana Furumiya

## Project Overview
The project investigates the relative contribution of institutional background and academic performance of graduate job placement prediction.

## Dataset
Job placement dataset
Link: https://www.kaggle.com/datasets/mahad049/job-placement-dataset

## Requirements
Install the required libraries using this command: `pip install pandas scikit-learn statsmodels matplotlib seaborn`

## How to Run the Project
1. Download the dataset from Kaggle
2. Place `job_placement.csv` in the same directory as the code
3. Install the required Python libraries

## Experimental Conditions
1. Full-feature model: Uses all available input features except placement_status and salary.
2. Without college name: Removes the college_name feature while retaining the remaining input features.
3. Without GPA: Removes the gpa feature while retaining the remaining input features.

## Machine Learning Configuration:
Algorithm: Random Forest Classifier
Number of trees: 100
Model random state: 42
Training/testing split: 80% / 20%
Data split random state: 28
Primary evaluation metric: Accuracy

## Limitations
The dataset sample set is 700 Bachelor's degree graduates from various universities in the USA. This dataset may not represent all graduates, industries, or geographic regions.
