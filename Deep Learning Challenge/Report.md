**Neural Network Model Analysis Report:**

1. Overview of the analysis: 

    The aim of this challenge was to develop a neural network model to predict the success of a company based on different financial features in the Alphabet Soup dataset. The purpose of this analysis will be to explain the data preprocessing, evaluate the model's preformance in compiling, training, and evaluating the model, and summarize the overall results so a recommendation can be suggested. 

2. Results: 

* Data Preprocessing

    * What variable(s) are the target(s) for your model?
      * The target variable is the 'IS_SUCCESSFUL' column.

    * What variable(s) are the features for your model?
      * The feature variables for my model were everything but the "IS_SUCCESSFUL" column. This includes "APPLICATION_TYPE", "AFFILATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT".

    * What variable(s) should be removed from the input data because they are neither targets nor features?
      * The "EIN" and "NAME" variables were removed from the imput data becasue they were neither targets or features.

* Compiling, Training, and Evaluating the Model

    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
      * My neural network model had 2 hidden layers and 1 output layer. For the first hidden layer there were 8 neurons and relu activation. For the second hidden layer there were 5 neurons and relu activation. For the output layer there were 1 unit and sigmoid activation. 

      * For my third attempt optimized neural network model there were 3 hidden layers and 1 output layer. For the first hidden layer there were 7 neurons and relu activation. For the second hidden layer there were 14 neurons and sigmoid activation. For the third hidden layer there were 21 neurons and sigmoid activation. For the output layer there were 1 unit and sigmoid activation. 

    * Were you able to achieve the target model performance?
      * I was not able to achieve the target model performance for either my neural network model or my optimized neural network model. 

    * What steps did you take in your attempts to increase model performance?
      * The steps I took to increase model performance in my attempts were to clean and remove feautres and trying different number of layers, activations, and epochs.  

3. Summary:

    * Overall the neural network model performance was able to achieve approximately 73% in predicting the classification outcome and was not able to achieve the target model performance. To increase the model performance, using a model that better shows the relationship between input features and the target would be beneficial. A way to achieve this would be to clean and remove the features better and to try different comninations of layers, activations, and epochs. 