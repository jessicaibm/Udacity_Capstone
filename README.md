# Udacity_Capstone
Udacity Data Science Nanodegree Capstone project: Create a Customer Segmentation Report for Arvato Financial Solutions

### Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [Data](#Data)
4. [File Descriptions](#File-Descriptions)
5. [Instructions](#Instructions)
6. [Acknowledgement](#Acknowledgement)

### Installation

This project requires **Python 3.x** and the following Python libraries installed:

- [Pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)


### Project Motivation
1. Customer Segmentation Report
  - Use unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.
2. Supervised Learning Model
  - Use the previous analysis to build a machine learning model that predicts whether or not each individual will respond to mail order campaign.
3. Kaggle Competition
   - Use a chosen model to make predictions on the mail order campaign data as part of a Kaggle Competition
   - Rank the individuals by how likely they are to convert to being a customer, and see how your modeling skills measure up against your fellow students.

### Data
Raw Data files:
Udacity_AZDIAS.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).<br>
Udacity_CUSTOMERS.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).<br>
Udacity_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign (training set); 42 982 persons (rows) x 367 (columns).
Udacity_MAILOUT.csv: Demographics data for individuals who were targets of a marketing campaign (testing set); 42 833 persons (rows) x 366 (columns).
DIAS Attributes - Values 2017.xlsx: A detailed mapping of data values for each feature in alphabetical order.
DIAS Information Levels - Attributes 2017.xlsx: A top-level list of attributes and descriptions, organized by informational category

Files created and exported within project:
customers_clean.csv: Result of Udacity_CUSTOMERS.csv after going through cleaning function within the notebook.
azdias_clean.csv: Result of Udacity_AZDIAS.csv after going through cleaning function within the notebook.
feat_info2.csv: DIAS Attributes - Values 2017.xlsx after undregoing manipulation within the notebook.
nan_df.csv: Dataframe of null values

kaggle_competition.csv: Entry to kaggle competition. Dataframe with two columns, one with the ID number for each individual in the "TEST" partition, the second column a measure of how likely each individual became a customer.


### File Descriptions


### Instructions:

### Acknowledgement

This dataset is provided by [AZ Direct GmbH](https://www.az-direct.com/site/en/). 
