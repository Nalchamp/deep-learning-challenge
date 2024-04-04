# Data Preprocessing

  1. What variable(s) are the target(s) for your model?
      The target variable is the "IS_SUCCESSFUL' column from application_df

  2. What variable(s) are features for your model?
      THe feature variables are very other column in the application_df

  3. What variable(s) should be removed from the input data because they are neither targets nor features?
       Both Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.

# Compliling, Training, and Evaluating

  1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
     I selectd 8 hidden nodes and 16 hidden nodes for my first attempt to see how the accuracy would be and how to adapt going further

  2. Were you able to acheive the target model performance?
     No I was unable to do that

  3. What steps did you take in your attempts to increase the model performance?
     Initially I attempted to add more layers, remove addiitional columns and increase the hidden nodes. Finally I switched the activation functions with each layer. ultimately this did not help.

# Summary

OVerall I could only achieve a 73% accuracy in for the learning model. Using a model with a better correlation between input and output would increase the prediction accuracy. By altering the data via clean up and possibly with different activation functions.
