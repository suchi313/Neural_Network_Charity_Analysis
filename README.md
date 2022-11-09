# Neural Network Charity Analysis 

## Purpose

By utlizing Machine Learning and Neural Networks, I used the features presented in the dataset to create a binary classifier that aided in the process of predicting if the applicants that are funded by the charitable organization - Alphabet Soup will be successful. The purpose of the challenge was to predict if charities will be succful if they receive funding. 

## Overview 

This challenge involved 3 deliverables:
- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model

## Resources 

Data Source: Charity_Data.csv
Software:
- Python 
- Pandas 
- NumPy 
- Matplotlib
- Google Colab

## Results

Initially, the dataset the organization received comprised of a number of columns that captured metadata about each organization: 
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

### Data Preprocessing for the Neural Network 

- The variable that is the *target* for the model - *IS_SUCCESSFUL Column* 
- The variables that are the features for the model - *APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.*
- There were 2 columns that were not targets or features for the dataset, I decided to drop them as they had no impact. *EIN and NAME*
