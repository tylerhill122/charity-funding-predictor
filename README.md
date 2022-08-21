# charity-funding-predictor

## Background

Use Machine Learning and Neural Networks to create a binary classifier that can predict whether applicants will be successful if funded by a fictional non-profit foundation.

### Step 1: Preprocess the Data

Use scikit-learn's `StandardScaler()` to preprocess the dataset before compiling, traning, and evaluating the neural network model.

* What variable(s) are the target(s) for your model?
    - The `IS-SUCCESSFUL` column will be the target for our model
* What variable(s) are the feature(s) for your model?
    - The other columns within the dataset will act as variables in the establishment of our model.

### Step 2: Compile, Train, and Evaluate the Model

Using TensorFlow and Keras, we will design a neural network, or deep learning model, to create a binary classification model that can predict if an organization will be successful if offered funding.

### Step 3: Optimize the Model

We are looking to optimize the model to achieve a target predictive accuracy higher than 75%. This may include measures such as adjusting the input data to ensure variables or outliers are not causing confusion in the model, adding more neurons to a hidden layer, or adding or reducing the number of epochs to the training regimen.

### Step 4: Write a Report on the Neural Network Model

This will provide a summary of the results of our model, and address a number of questions we had to answer in the creation of this model.