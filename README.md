Overview of the analysis: Explain the purpose of this analysis.
-The purpose of this analysis is to make an accurate neuranl network model using all the necessary tools and variables in order to have an optimal result. First I clean the data base to only the columns neccesary to work with,then grouping the data outliers of the columns: application_type and classification in a column named: other, then converted the object columns into onehotencoder to have just binary numbers dataset, and finally spliting the data, defining the variables, fitting the data, scaling the data and training, compiling and evaluating the model

Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
What variable(s) are considered the target(s) for your model?
-IS_SUCCESSFUL variable

What variable(s) are considered to be the features for your model?

<img width="615" alt="Captura de Pantalla 2023-02-23 a la(s) 18 13 15" src="https://user-images.githubusercontent.com/72363865/221060296-44992644-6e36-4a3c-aa04-22b1d2ca2def.png">


What variable(s) are neither targets nor features, and should be removed from the input data?
- 'EIN','NAME' variables


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
-50,60,70 neurons, 3 layers, relu and sigmoid
the reason to use this information is to tell 

Were you able to achieve the target model performance?

What steps did you take to try and increase model performance?


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
