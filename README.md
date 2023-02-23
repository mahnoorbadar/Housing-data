# Housing-data
StandardScaler is used as it removes the mean and scales each feature/variable to unit variance.
First, we need to divide our data into features (X) and labels (y). The dataframe gets divided into X_train,X_test , y_train and y_test.
X_train and y_train sets are used for training and fitting the model.
A Sequential model is imported from keras to arrange the Keras layers in a sequential order so that the data flows from one layer to another layer 
in the given order until the data finally reaches the output layer.
