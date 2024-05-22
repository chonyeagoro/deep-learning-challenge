# deep-learning-challenge


## Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special considerations for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively


# Overview of the analysis: 
## Explain the purpose of this analysis.

The purpose of this analysis was to create a tool to see which applicants that were selected for funding would have the best chance of success in their ventures. 

## Results: Using bulleted lists and images to support your answers, address the following questions:

### Data Preprocessing

What variable(s) are the target(s) for your model?

- The target is the "y" which is the "IS_SUCCESSFUL" column. 

What variable(s) are the features for your model?

- The features is the "X" which is every column except the "IS_SUCCESSFUL" column which are the following: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS—Active status, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. 
  
What variable(s) should be removed from the input data because they are neither targets nor features?

- The variables that should be removed are EIN and NAME. 

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

For my neural netwrk model, I used 

Were you able to achieve the target model performance?

- No. I tried more than three times and the best I could get was an accuracy of 0.7305 (73.05%)
  
What steps did you take in your attempts to increase model performance?

I did the following:
I increased the epoch 


## Summary

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
