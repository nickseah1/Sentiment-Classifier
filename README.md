# Natural Language Processing Sentiment Classifier 


## Introduction: The purpose of this project was to build a model that can accurately predict the sentiment of any input sentence. This is useful when trying process customer feedback as it would be absurd to expect someone to read through all of that data.
r
## Methodology

1) Import data 
2) Data Cleaning 
3) Grid Serach CV for paramater selection
4) Train the model with a random forest classifier with it's meritable parameteres
5) Evaluate the model
6) Write a function to enable custom input


## Conclusion

The model performated at ~96% Accuracy

## Potential Future improvements

1) Try more parameters during cross-validation
2) Try XGboost
3) Train a convolutional nueral network
4) Add more output nodes so it can predict more categories than positive or negative. Perhaps neutral because sentiments such as surprise could be positive or negative. This would likely reduce model accuracy.
