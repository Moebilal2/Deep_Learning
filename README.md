# Deep_Learning
## OVERVIEW
  The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With techniques of machine learning and neural networks, the features are used in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. The dataset contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization

## REUSLTS
- Data processing:
  The targer for this dataset is the column (IS_SUCCESSFUL) which indicates whether the money used effectively, the features are all the other columns except that, two columns were dropped (EIN, Name) since they are irrelevant to the feature nor the target.
- Compiling, Training, and evaluating the models:
  The first try, the model tested with 3 layers with 8 nodes for the first layer and 5 nodes for the second layer and the output layer with 1 node, the activation functions used were RELU for the hidden layers, and Sigmoid function for the output layer. This model acheived accuracy of 0.7325. Then hypertuning was used to improve the model by trying different layers numbers and nodes number and choose the best score, the results was accuracy of 0.73154, this score was acheived using 6 layers and 16 total nodes.
## Summary:
  Even with the hypertuned model the highest accuracy was 0.7325, which is less than the target accuracy which is higher than 75%, my recommendation is to try different classification models to see if we can get better accuracy.
