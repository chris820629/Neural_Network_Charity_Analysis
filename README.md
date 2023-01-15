# Neural_Network_Charity_Analysis

## Overview of the analysis
Help the foundation predict where to make investments. Using the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Results
### Data Processing
- IS_SUCCESFful column is considered the target column for the model, 1 being the program has the successful outcome
- Application type, affiliation, classification, use_case, organization, status, income_amt, ask_amt
- EIN, NAME, status, special_considerations are non critical features which were removed
### Compiling, Training,and Evaluating the Model
- I used 2 hidden layers with 8 and 4 neurons each since the neuron numbers typically decreases along the neural network hiearchy. 
- The highest score I reached was 74.6% 
- Keeping the same network architecture but removing the non-critical columns as well as increasing the binning amount with more granularity
## Summary
- from my observations, the model did improve slightly by increasing hidden layer but also by reducing the number of neurons for the 1st hidden layer. There was slightly more improvement from adding more binning for a few categories with higher unique values, such as application_type and classification. 