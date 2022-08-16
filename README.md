# Neural_Network_Charity_Analysis
## Overview of the analysis: Explain the purpose of this analysis.
The aim of this analysis is to help Alphabet Soup where to make investments by predicting which organizations are worth donating and which are risky. By using Machine Learning and Neural Networks, this analysis will be able to create a binary classifier that can do the prediction of whether the applicants will be succesful if funded by AlphabetSoup.

## Results

### Data Preprocessing

In this step, the charity_data.csv will be processed by reading and indentifying the following variables:
Target Variable: IS_SUCCESSFUL
Features variable: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
Variables removed: EIN and NAME

### Compiling, Training, and Evaluating the Model

Once having the inputs that are going to determine the number of neurons and layers, the binary classification model is going to be compiled, trained and evaluated in order to calculate the model's loss and accuracy.
There have been selected 80 and 30 neurons for the first and second hidden layer, respectively. Also, for speeding up the training process and getting the best performance
How many neurons, layers, and activation functions did you select for your neural network model, and why?

The model accuracy got 72.69%, which is not properly for satisfying the target model performance required
Were you able to achieve the target model performance?

What steps did you take to try and increase model performance?
There were some steps done for increasing model performance, which were:
1. Increased Training duration from 100 to 200. 
2. Changing activation function of hidden layer from relu to tanh.
3. Adding more hidden layers. 

## Summary: 

The results of the deep learning model for predicting loan candidate success were roughly 73%, which did not reach the accuracy goal.
As a recommendation for a model resolving this issue would be the Random Forest Classification considering that is a less risk of overfitting, less computational expensive and better to be more effective with less data.
