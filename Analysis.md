# ds_2024_module_21_deep-learning-challenge
advanced machine learning
Data Preprocessing
- The target variable is the 'IS_SUCCESSFUL' column from application_df
- The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe
- Both 'EIN' 'NAME' SPECIAL_CONSIDERATIONS, STATUS columns were dropped/removed, because they were neither targets nor features for the dataset.

Compiling, Training, and Evaluating the Model
- In the first attempt, i used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 -- these were just random guesses from which to iterate upon in the second try.
- I was not able to achieve the 75% model accuracy target
- I added more layers, removed more columns, added additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy. 

Overall, the deep learning model was around 73% accurate in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached. 