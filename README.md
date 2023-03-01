# Neural_Network_Charity_Analysis
## Project Overview
Using machine learning and neural netowrks we utilize these tools to provide a dataset to help Beks create a binary classifier to predict whether applicants will be successful if funded by Alphabet Soup. Step by step we, preprocessing data for a neural network model, compile, train, and evaluate the model, and lastly optimize the model.
## Results
### What variable(s) are considered the target(s) for your model?

Analyzing the target to see if it is succeesful in dataframe and successfully funded by alphabetsoup


### What variable(s) are considered the feature(s) for your model?

The variable: "IS_SUCCESSFUL" column is the feature chosen for this dataset.


### What variable(s) are neither targets nor features, and should be removed from the input data?

In the input data, EIN and NAME columns will not increase the accuracy of the model, can be removed to improve the result of the code efficiency.

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

In the optimized neural network model, layer 1 started with 120 neurons with a relu activation. In the following layer 2, it decreased to 80 neurons and continued with the relu activation. Lastly following, sigmoid activation seemed to be more appropriate for layer 3 (40 neurons) and layer 4 (20 neurons).

### Were you able to achieve the target model performance?

the target for the model was to achieve 75%, but with model with what we created resulted in a 72%

![image](https://user-images.githubusercontent.com/114195211/222290061-aa0c9a24-687f-4bf1-b29c-fc1c866a6f97.png)

### What steps did you take to try and increase model performance?

Steps we did to increase a higher percentage model performance, first dropping columns special_considerations & status while increasing number of neurons and layers.

## Summary

With everything we could while following instructions, relu and sigmoid activations resulted in a 72% accuracy with the model created with the data set. 
