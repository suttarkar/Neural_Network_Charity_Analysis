# Neural Network Charity Analysis

## Purpose
Building a deep learning model that helps Alphabet Soup predict whether applicants will be successful if given a grant.

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
The target variable of the model is 'IS_SUCCESSFUL'

What variable(s) are considered to be the features for your model?
The variables that would be considered features would be 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ASK_AMT', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'

What variable(s) are neither targets nor features, and should be removed from the input data?
'NAME' and 'EIN' are the variables that need to be removed from the input data.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used 75 neurons on the first layer and 25 neurons on the second layer. The activation functions used for both were relu. I used this amount of nearons because I used trial and error to find a good balance.

Were you able to achieve the target model performance?
No, I was unable to meet 75%. The closest i was able to go was 73%

What steps did you take to try and increase model performance?
At first, I tried to increase the ampunt of neurons. After that I tried to decrease the number of neurons. Last, I tried to get rid of the outliers by getting rid of the 99th percentile and the 1st percentile(this ended up having the worst accuracy).

## Summary
In the end, I was unable to pass 75% accuracy. In my attempts I focused more on the amount of neurons, and there was not much affect. If I were to focus on preparing the data even more for the model, the accuracy will have a much better chance of increasing.

