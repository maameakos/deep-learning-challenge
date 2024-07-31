OVERVIEW:

The analysis concerns the nonprofit foundation Alphabet Soup, which wants a tool to help it select the applicants for funding with the best chance of success in their ventures. Using my knowledge of machine learning and neural networks, I use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

RESULTS:

Data Preprocessing

1.	What variable(s) are the target(s) for your model?

•	The variable target for the model is “IS SUCCESSFUL” column

2.	What variable(s) are the features of your model?

•	The features variable for the model are the remaining columns after dropping the “EIN” and “NAME column from the original dataframe

3.	What variable(s) should be removed from the input data because they are neither targets nor features?

•	The “EIN” and “NAME should be removed because they are neither targets nor 
  features.

Compiling, Training, and Evaluating the Model:

4.	How many neurons, layers, and activation functions did you select for your neural network model, and why?

•	Initially, I used 8 hidden_nodes_layer1 and 5 hidden_nodes_layers2; they were just random guesses and knowledge from what I learned in class

5.	Were you able to achieve the target model performance?

•	I was not able to achieve the target model performance; however, I came close to 73%

6.	What steps did you take in your attempts to increase model performance?

•	I dropped fewer columns and added more layers and additional hidden nodes to try and achieve higher model performance.

Summary:

•	In summary, the model was closer to 73% accuracy in prediction. To achieve a higher prediction accuracy, I believe using a model with a greater correlation to input data will result in an accurate of output. Different models could solve this classification problem because the model’s accuracy is determined by how many labels it predicts correctly.





![image](https://github.com/user-attachments/assets/3f8cfb8c-f325-4756-b334-82293f9d8d12)
