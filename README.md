# deep-learning-challenge

Run the ColabStarter_Code.ipynb in Google Colab.

Run the Starter_Code.ipynb in Jupyter Notebook.

Run the ColabAlphabetSoupCharity_Optimization.ipynb in Google Colab.

Run the AlphabetSoupCharity_Optimization.ipynb in Jupyter Notebook. 

The AlphabetSoupCharity.h5 and AlphabetSoupCharity_Optimization.h5 files are products of running the above Google Colab and Jupyter Notebook files.

Chat GPT was used to debug code. 

My Written Report on the Neural Network Model is below.

1. OVERVIEW 
The purpose of the analysis is to build a neural network model to help determine whether or not organizations funded by Alphabet Soup would be succesful.

2. RESULTS

Data Preprocessing

  a. The target varaible for the model is "IS_SUCCESSFUL."
  b. The variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS.
  c. Variables that were removed from the input data were EIN and NAME.

Compiling, Training and Evaluating the Model

  d. The neural network architecture consists of:
  Input Layer - 34 input featuers
  First Hidden Layer - 128 neurons with ReLU activation
  Second Hidden Layer - 64 neurons with ReLU activation
  Output Layer - 1 neuron with a sigmoid activation

  e. The model achieved an accuracy of 72-73% on the test dataset. There is room for improvement.

  f. Steps taken to attempt to increase model performance:
  Early Stopping
  Dropout
  Batch Normalization
  Hyperparameter Tuning

3. SUMMARY

The results show there is opportunity for a stronger model, but we are on the right track for accuracy. 

Another recommendation for a different model would be Random Forest, which could produce better results. A benefit of this could be faster data training and less of a need for a massive dataset in order to be effective.

I would probably go with a Random Forest model next time to see if we could improve this model since the accuracy is not super high.
