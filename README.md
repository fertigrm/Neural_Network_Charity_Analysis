# Neural_Network_Charity_Analysis
## Overview of Analysis
The purpose of this analysis was to use deep learning neural network models with the help of TensorFlow and Python. With these tools we analyzed the success of charity donations. The following steps were used:
- Preprocess data for our Neural Network Model
- Compile, train and evaluate the Neural Network Model
- Optimize the Neural Network Model
## Resources Used
- Python and its many libraries
- Anaconda
- Jupyter Notebook
## Results of Analysis
## Data Preprocessing
- Columns 'EIN' and 'NAME' where dropped/removed from the data
- Columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION',  'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' were the features for our Neural Network Model
## Compile, Train, and Evaluate the Model
- This deep learning Neural Network Model contains two hidden layers with 90 and 40 neurons each. We used tanh for the activation of the hidden layers, our output layers activation was Sigmoid.
- This model unfortunatley did not reach the goal of 75% success, it would not be reliable to aid in prediction of charity donations.
- To improve the model we tried up to 4 hidden layers with different activations and different numbers of neurons however, the model above was the highest % successful.
## Summary of Anaylsis
This deep learning Neural Network model unfortunately did not reach the target goal of 75% accuracy. By not reaching 75% which is a reasonable goal to get, I would not recommend this model to be used.

