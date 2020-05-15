# Starbucks-Capstone-Udacity-Data-Science-Nanodegree
##MY BLog  https://medium.com/@devanshsachan007/starbucks-capstone-udacity-data-science-nanodegree-70b83d4ec256
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

Here is the schema and explanation of each variable in the files:

`portfolio.json`
- id (string) - offer id
- offer_type (string) - the type of offer ie BOGO, discount, informational
- difficulty (int) - the minimum required to spend to complete an offer
- reward (int) - the reward is given for completing an offer
- duration (int) - time for the offer to be open, in days
- channels (list of strings)

`profile.json`
- age (int) - age of the customer
- became_member_on (int) - the date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

`transcript.json`
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since the start of the test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record


## Acknowledgements
Thank you to Starbucks for providing the data
