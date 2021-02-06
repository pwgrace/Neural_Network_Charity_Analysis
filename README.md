# Neural_Network_Charity_Analysis
## Overview of the analysis
#### The purpose of this analysis is to use a neural network to predict whether applicants will be successful if funded by Alphabet Soup. 
## Results
### Data Prepocessing
#### The target variable is the category "IsSucessful". The features include the application type, affiliation, classification, use case, organization, income, ask amount, and special considerations. The EIN and name variables were removed from the data set. 
### Compiling, Training, and Evaluating the Model
#### The initial run used 2 layers with 80 nodes in the first layer and 30 nodes in the second layer. There were 3 activation functions including the output layer. The initial run parameters were given by the starter code.
#### We were not able to produce a 75% accuracy rate with 3 attempts. During the first attempt we changed the nodes to 100 and 50, respectively, and received an accuracy of 66%. In the second attempt we changed the first layer activation function to tanh and increased the 2nd layer node to 80. The accuracy was 65%. We added a 3rd layer in the third attempt and were suprised to see the accuracy fall to 47%. 
## Summary
#### The results are promissing and with more attempts at optimization we would likely make progress. We could remove irrelevant variables and continue to alter the activation functions. We could also increase the number of epochs. 
