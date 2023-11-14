
Preprocess the Data
Create a dataframe and identify the target and feature variables in the dataset.
Drop unnecessary columns
Determine the number of unique values in each column 
For columns with more than 10 unique values, determine the number of data points for each unique value 
Create a new value called Other that contains rare categorical variables
Create a feature array, X, and a target array, y by using the preprocessed data
Split the preprocessed data into training and testing datasets 
Scale the data by using a StandardScaler that has been fitted to the training data 

Create a neural network model with a defined number of input features and nodes for each layer
Create hidden layers and an output layer with appropriate activation functions
Compile and train the model
Evaluate the model using the test data to determine the loss and accuracy 
Export your results to an HDF5 file 
Optimize the Model 

Repeat the preprocessing steps in a new Jupyter notebook (4 points)
Create a new neural network model, implementing at least 3 model optimization methods. I added additional neurons and layers and changed activation functions, which improved the accuracy.
