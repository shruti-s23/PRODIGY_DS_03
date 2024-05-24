## Overview
This project focuses on building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used for this project is the Bank Marketing dataset obtained from the UCI Machine Learning Repository.

## Dataset
The raw dataset `bank-full.csv` was acquired from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing). It contains demographic and behavioral data of customers, including features such as age, job, marital status, education, previous marketing campaign interactions, and whether the customer made a purchase.

## Jupyter Notebook
The Jupyter notebook `TASK03.ipynb` contains the actual code for preprocessing the dataset, training the decision tree classifier, and evaluating its performance.
The provided code implements a decision tree classifier to predict customer purchases based on demographic and behavioral data from the Bank Marketing dataset. The dataset is loaded using pandas, and categorical variables are encoded into numerical form. The target variable is transformed to binary values representing purchase decisions. The dataset is then split into training and testing sets for model evaluation. A decision tree classifier is trained on the training data and used to make predictions on the testing data. The accuracy, classification report, and confusion matrix are calculated to assess the model's performance. Overall, the code demonstrates the process of preprocessing data, training a classifier, and evaluating its performance in a binary classification task.

## How to Use
1. **Accessing the Dataset**: The raw dataset `bank-full.csv` can be accessed from the provided link, or in the repository itself.
2. **Running the Jupyter Notebook**: If you wish to replicate the data cleaning process, refer to the Jupyter notebook file named `TASK03.ipynb` provided in the repository.
3. **Interpreting the Results**: Analyze the output generated in the notebook to understand and interpret the performance of the decision tree classifier.

