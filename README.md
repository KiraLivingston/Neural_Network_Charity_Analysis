# Neural_Network_Charity_Analysis

## Overview of the Analysis
  This challenge's purpose was to use TensorFlow and design a deep learning model or neural network to predict if an Alphabet Soup Funded organiztion would be successful according to the Dataset.
  
## Results
* Data Preprocessing
The target variable for this model was the "IS_SUCCESSFUL" Column.
The feature variables for this model were all columns other than the target variable and dropped variables.
The EIN and NAME variables were dropped from the dataset as they had no impact on the outcome of the analysis.

* Compiling, Training, and Evaluating the Model
![Compiling](Trained_Model.png)

There were 2 layers that were hidden, the first layer had 80 neurons, the second had 30 neurons.

![Accuracy](Model_Accuracy.png)
