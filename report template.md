# Module 21 Report Template 

## Overview of the Analysis

The purpose of the analysis was to design a deep learning model for the non-profit organization Alphabet Soup that can predict if the organization will be successful based on the dataset.  I used the dataset charity_data.csv which consisted to the EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL. 

## Results 

Data Preprocessing:
- The target variable of the model is the "IS_SUCCESSFUL" column in the dataset.
- The model's features are all the other columns in the dataset.
- The variables removed from the dataset are "EIN" AND "NAME",
 
Compiling, Training, and Evaluating the Model:
- For my model, I used a first hidden layer, a second hidden layer, and an output layer for a total of 3 layers.  I used the relu activation on the first two layers and the sigmoid on the output layer.  For my first attempt, I used 80 (first layer), 30(second layer), and 1(third layer) units as a starting point. 
- No, I was not able to reach the 75% target model performance. 
- I tried adding a fourth hidden layer, raised my units from the first attempt, changed the activation, and added more epochs.

## Summary

The overall results of this model did not reach the optimal performance as it never reached higher than 72%. However, it did get very close to the achieved accuracy and could reach 75% or higher by continuing to add layers, changing the activation, picking different unit amounts, and trying different ways to preprocess the input data.
