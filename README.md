# UCI Adult Dataset Analysis
Capstone Project

### Exploratory Data Analysis (EDA)
This is a very popular dataset and has been used in many analysis projects. Some of them will be referenced later. Following is the step by step EDA that has been done using various Python libraries

Link to the dataset: https://archive.ics.uci.edu/ml/datasets/Adult

#### Objective
This is a classification problem. Objective of the project is to determine whether a person makes $50K or not given the various demographic factors and to identify which factors are the most contributing in predicting or detrmining the income.

#### Downloading the Dataset
We are downloading the dataset from this link provided in the main page of the repository: https://archive.ics.uci.edu/ml/machine-learning-databases/adult/. We will use the following 2 files:
* adult.data - contains 32,561 instances
* adult.names - contains the column names and legends
* adult.test - contains 16,281 instances
We will merge the adult.data and adult.test datasets vertically for our project as we will split them through train-test split later on
Notably, we need to change all 3 files to .csv to be able to upload to Jupyter notebook
