# Alphabet Soup Deep Learning Model Report

## Overview of the Analysis
The purpose of this analysis was to develop a deep learning model using neural networks to predict whether an organization funded by Alphabet Soup would be successful based on various features provided in the dataset. The goal was to achieve a target predictive accuracy higher than 75%.

## Results

### Data Preprocessing

- **Target Variable(s):**
  - The target variable for our model is 'IS_SUCCESSFUL', which indicates whether the funding provided by Alphabet Soup was successful (1) or not (0).

- **Features:**
  - The features for our model include various columns such as 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and others.

- **Variables to Remove:**
  - We removed the 'EIN', 'NAME', and ''ASK_AMT'' columns from the input data as they were neither targets nor features and would not contribute to the predictive power of the model.

### Compiling, Training, and Evaluating the Model

- **Neurons, Layers, and Activation Functions:**
  - We selected a deep neural network architecture with three hidden layers consisting of 100 and 25 neurons, respectively. The activation function used in each hidden layer was ReLU.

- **Achieving Target Model Performance:**
  - No, we were not able to achieve the target model performance with an accuracy higher than 75%.

- **Steps Taken to Increase Model Performance:**
  - Data preprocessing including dropping non-beneficial columns, scaling features, and encoding categorical variables.
  - Experimentation with different architectures and hyperparameters.
  
## Summary

In summary, the deep learning model we developed could not achieve the target predictive accuracy of over 75%. However, there is still room for improvement. For further enhancement, we could explore different activation functions, perform feature engineering, use more advanced techniques such as transfer learning, and try ensemble methods.

## Repository Contents

- `AlphabetSoupCharity_Optimization.ipynb`: Jupyter Notebook containing the code for data preprocessing, model development, and evaluation.
- `AlphabetSoupCharity_Optimization.h5`: HDF5 file containing the optimized deep learning model.
- `README.md`: This markdown file summarizing the report.

## Dependencies

- pandas
- numpy
- tensorflow
- scikit-learn

