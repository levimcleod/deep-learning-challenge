# deep-learning-challenge

Overview of the analysis: We created a neural network model to predict whether applicants will be successful in their venture if given funding using a binary classifier.

# Results:

## Data Preprocessing

- "IS_SUCCESSFUL" is our target variable

- "APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT" are our features

- The EIN and NAME columns are removed from the input data because they are neither targets nor features

## Compiling, Training, and Evaluating the Model

- Our model has two dense layers and an additional output layer. The first dense layer uses 10 neurons with the relu activation function. The second dense layer uses 6 neurons with the tanh activation function. The ouput layer uses a single neuron with the sigmoid activation function. 

- After taking several steps to increase the model's accuracy, our model did not exceed 73%. Steps to improve our model's accuracy includes tuning the hyperparameters.

Summary: We recommend gathering more funding data in order to train the model on a more robust dataset. With a more robust dataset, we can expect our model's accuracy to improve drastically.