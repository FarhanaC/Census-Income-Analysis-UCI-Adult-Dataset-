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

#### Dataset Attributes
This is a multivariate datatset, as a result we will need to consider multiple variables, their relationship and influence on the target valrable - income (>50K or <50K).
**Attribute characteristic:** Both categorical and integer attributes are used
**Number of instances:** 48,842
**Number of attributes:** 14
**Missing values:** Yes

#### <u>List of Attributes:<u>
* **Age:** continuous
* **Workclass:** Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. 
* **fnlwgt:** final weight; continuous
* **Education:** Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
* **Education-num:** continuous.
* **Marital-status:** Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. 
* **Occupation:** Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
* **Relationship:** Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
* **Race:** White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. 
* **Sex:** Female, Male.
* **Capital-gain:** continuous.
* **Capital-loss:** continuous.
* **Hours-per-week:** continuous.
* **Native-country:** United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
