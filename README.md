# Neural_Network_Charity_Analysis

## Overview of Analysis
The purpose of this analysis is to help this company decide which organizations are worth the risk of donating to by building a deep learning model.

## Results

### Data Preprocessing
* IS_SUCCESSFUL was the target variable
* The feature variables were APPLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* EIN and NAME were neither targets nor features and were removed

### Compiling, Training, and Evaluating the Model
* I used two hidden layers with 12 and 4 neurons. I also used 3 different activation functions.
* I was not able to reach target performance.
* To optimize the model, I first changed the second layer's activation function to tanh. Next, I increased the number of nodes in my first layer from 7 to 12. Finally, I doubled the number of epochs from 150 to 300.

## Summary
My model was not successful and I would not recommend using it in its current state to help with the analysis. I would recommend maybe increasing the number of nodes in the second layer as well and even trying the addition of a third layer.
