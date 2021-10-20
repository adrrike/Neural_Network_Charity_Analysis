# Neural_Network_Charity_Analysis

## Overview:
To use neurial networks to analyze the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded.

## Analysis:

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The "IS_SUCCESSFUL" column. 

What variable(s) are considered to be the features for your model?
- Application type, ask amount, income amount, special considerations

What variable(s) are neither targets nor features, and should be removed from the input data?
- Name and EIN number

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

![attempt2](https://user-images.githubusercontent.com/84742544/138150335-feaf55f7-2cac-4865-8d79-0bd8bba1ad2e.PNG)


- Adding additional neurons, layers and differt activation functions can help achieve a better accuracy rate. 

Were you able to achieve the target model performance?
- No, every iteration of optimization only achieved about 73%. 

What steps did you take to try and increase model performance?
- Changing number of hidden layers, neurons within each layer and activation function. 

![attempt3](https://user-images.githubusercontent.com/84742544/138150327-5a0f0b12-8452-4ffc-8743-4b115fc15614.PNG)
![attempt4](https://user-images.githubusercontent.com/84742544/138150334-60703845-a4fa-4391-83af-88a1f0bcaeca.PNG)



## Summary: Summarize the overall results of the deep learning model.
- Overall the optimized network failed to meet the 75% accuracy goal. 

- I would recommend unsupervised machine learning model such as a cluster analysis. 

