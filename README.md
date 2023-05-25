# deep-learning-challenge

#Report

## Overview
The purpose of this analysis was to build a model to predict if an applicant would be a good candidate to receive funding based on their likely hood of success.

## Results
I created and ran a model with multiple hidden layers. I first tried 5 nodes in each hidden layer which resulted in less than 70% accuracy. I then tried 10 nodes in each layer which resulted in less than 73% accuracy. Finally I tried 16 nodes and this resulted in slightly above 74% accuracy.

## Data PreProcessing
What variable(s) are the target(s) for your model?
    - the target is the "IS_SUCCESFUL" variable
What variable(s) are the features for your model?
    - there are multiple features in the model to include "ask amount, application type, special considerations" and more
What variable(s) should be removed from the input data because they are neither targets nor features?
    - 'EIN','NAME'

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - 2 hidden layers with 16 nodes
Were you able to achieve the target model performance?
    - no I was no able to achieve 75% accuracy.
What steps did you take in your attempts to increase model performance?
    - I increased the amount of nodes in each layer and then re-ran the model.

    
