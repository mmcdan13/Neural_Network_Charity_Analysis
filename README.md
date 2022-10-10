# Neural_Network_Charity_Analysis

## Overview of the Analysis

The purpose of this analysis is to help non-profit, Alphabet Soup, determine which organizations to donate to by creating a neural network model that will predict whether applicants will be successful if funded by Alphabet Soup.

## Results

### Preprocessing

* In this model,the target was the column IS_SUCCESSFUL.
* The features for the model was APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS ASK_AMT 
IS_SUCCESSFUL.
* The variables EIN and NAME are neither targets nor features, and were removed from the input data. 
### Compiling, Training, and Evaluating the Model
* I selected 3 hidden layers with neurons of 110, 50, and 25. I chose the neurons amount 110 because the input number was 55 and a good rule of thumb is to choose neurons between 2-3x the input number. 
* My model achieved the model performance of 73.1% accurate thus I was not able to achieve the target model performance. 
* To try and increase model performance:
    * I increased the number of neurons in the input layer from 80 to 110, I
    * I increased the number of hidden layers from 2 to 3 
    * I changed the activation functions from ReLU to Tanh 

## Summary

I think a Random Forest model might be another model that could solve this classification problem, because Random Forest models are great for tabular data which we have in this problem, and are faster than deep learning models.