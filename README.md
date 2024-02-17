# Iris-machine-Learning-model

The provided Python code focuses on implementing a classification model using the k-nearest neighbors (KNN) algorithm with the Iris dataset. Here's a concise summary of the code:

Data Loading and Exploration:

The Iris dataset is loaded into a Pandas DataFrame.
The initial rows of the dataset are printed to understand its structure.
Data Preprocessing:

Features (X) and the target variable (y) are separated.
Categorical labels in the 'Species' column are encoded into numerical values using LabelEncoder.
Data Splitting:

The dataset is split into training and testing sets (80% training, 20% testing) using train_test_split.
Model Training:

A K-Nearest Neighbors model is instantiated with n_neighbors set to 3.
The model is trained using the training set.
Prediction:

The trained model is used to make predictions on the test set.
Model Evaluation:

The accuracy of the model is calculated by comparing predicted values to actual values in the test set using accuracy_score.
The accuracy is printed, providing a measure of the model's performance on unseen data.
In summary, the code showcases a typical machine learning workflow, encompassing data loading, preprocessing, model training, prediction, and evaluation. The KNN algorithm is employed for classification, and the accuracy metric is used to assess the model's performance.
