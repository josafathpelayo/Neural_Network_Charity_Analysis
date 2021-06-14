# Neural_Network_Charity_Analysis
The purpose of this project is to use my knowledge of machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Data used was from a CSV file that contained over 34,000 orginizations that recieved funding from Alphabet Soup over several years. Tensorflow and deep machine learning skills were applied for this analysis.

## Results
- Data Preprocessing
    - Variables that was considered our target was the IS_SUCCESSFUL column from the data set.
    - Variable considered to be features for our model was every column execpt 'EIN', 'NAME' from our dataset
    - Variables that are neither targets nor features are 'EIN', 'NAME'. 
 
 - Compiling, Training, and evaluating the Model
    - I was not able to hit the target goal of 75%
    - I tried increaing the epoch totals, dropping more columns that would affect more the outcome, and adding more hidden layers

## Summary
The Model ended up having an accuracy of  64% for the neural model and when optimized, the accuracy score was 63.7%. Not a drastic difference as the target goal was 75%. Although the target goal was missed, one can still optimize the model by by having noisy variables are removed from features, adding neurons to hidden layers, adding more hidden layers, and increasing or decreasing the total epochs in the model. Overall, This model showcased the importance of neural networks, but factors within the model itself can be changed to optimize the accuracy. 
