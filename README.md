# Neural_Network_Charity_Analysis

## Overview of the analysis 

- The project aims to use machine learning and neural network to create a binary classifier to predict if applicants will be successful if funded by Alphabet Soup.

## Results 

- Data Preprocessing
  
  - What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL column.
  - What variable(s) are considered to be the features for your model? APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
  - What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME

- Compiling, Training, and Evaluating the Model

  - How many neurons, layers, and activation functions did you select for your neural network model, and why? Following the instruction code, I use 80 and 30 respectively for the number of neurons and 2 layers, and relu as activation function for input and hidden layers while using sigmoid as activation function for output layer. 
  
  - Were you able to achieve the target model performance? However, none of them helps me to achieve the target model performance. 
  
  - What steps did you take to try and increase model performance? I then try different ways to optimize the accuracy score. I add one more hidden layer, using different       activation function which is “tahn” and increase the neurons from 80 to 120 in the first hidden layers.

## Summary

- To sum up, the deep learning model did not perform well enough to achieve the accuracy target. However, we could use other machine learning model to optimize its result. 
