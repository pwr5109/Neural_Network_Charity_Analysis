# Neural_Network_Charity_Analysis


## Objective
The Purpose of this analysis is to build a model that can predict the suitability of potential clients to provide monetary support to the Alphabet Soup's mission.

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model? 
- The target variable in this model is the "IS_SUCCESFUL" since we want the model to determine if the applicants will be succesful if funded by Alphabet Soup

What variable(s) are considered to be the features for your model?
- The features variables are everything except for the target: "EIN" and "NAME".

What variable(s) are neither targets nor features, and should be removed from the input data?
- The "EIN" and "NAME" columns should be removed. In the opitmization, I removed status to reduce the noise within the model to improve the data.

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I started with 10 neurons in the first layer and 4 in the following layer, and after I ran the analysis I saw the model was performing at 71% then I increased the the number of neurons and ran the Analysis again, which resulted in around 73% accuracy. 

Were you able to achieve the target model performance?
- I results wasn't able to achieve the desired Analysis targets.

What steps did you take to try and increase model performance?
- I then removed some columns to remove noise if possible, which didn't work out, so the next few steps was to add a 3rd layer and add more neruons to each layer. After all that, The activation functions and tested different combinations of RELU, Sigmoid, etc. 