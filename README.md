# Starbucks-Capstone-Udacity-Data-Science-Nanodegree
#### DEVANSH SACHAN

## Libraries
pandas
numpy
math
json
matplotlib.pyplot as plt
pickle
sklearn:
- MultiLabelBinarizer
- train_test_split
- GridSearchCV
- RandomForestClassifier
- DecisionTreeClassifier
- accuracy_score,f1_score

## Project Motivation

It is the Starbuck's Capstone Challenge of the Data Scientist Nanodegree in Udacity. We get the dataset from the program that creates the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers. We want to make a recommendation engine that recommends Starbucks which offer should be sent to a particular customer.

We are interested to answer the following two questions:
1. Which offer should be sent to a particular customer to let the customer buy more?
2. Which demographic groups respond best to which offer type?

## File Description
data:
  - portfolio.json: dataset containing various offers and associated data
  - profile.json: dataset containing all customer records
  - transcript.json: All customer-store interactions (offers and transactions)
Starbucks_Capstone_notebook.ipynb: Python notebook that explores the data and builds a classification model
randomforestclassifier.pkl: Pickle file of fitted model

## Acknowledgements
Thank you to Starbucks for providing the data
