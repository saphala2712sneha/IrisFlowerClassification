IRIS FLOWER CLASSIFICATION 

This project focuses on classifying iris flowers into three species—Setosa, Versicolor, and Virginica—using the classic Iris dataset. The dataset contains 150 samples, each with four features: sepal length, sepal width, petal length, and petal width, measured in centimeters. The goal is to build a machine learning model that can accurately predict the species based on these measurements.

The workflow begins with loading and preprocessing the data using pandas. Unnecessary columns, such as an ID column if present, are removed, and the categorical species labels are converted into numerical classes suitable for model training. The data is then split into training and testing sets with an 80-20 ratio to evaluate how well the model generalizes to unseen data.

A Support Vector Machine (SVM) classifier from scikit-learn is trained on the training set. After training, the model makes predictions on the test set, and its accuracy is evaluated using the accuracy score metric. The model’s ability to generalize is demonstrated by its performance on this separate test data.

Additionally, the project shows how to use the trained model to predict the species of new, custom input data points. To enable easy reuse and deployment, the trained model is saved to a file using Python’s pickle module. This saved model can be loaded later without retraining, facilitating quick predictions on new data.

This project uses popular Python libraries including numpy, pandas, matplotlib, scikit-learn, and pickle. It serves as a great introduction to supervised machine learning, demonstrating data preprocessing, model training, evaluation, and persistence. The Iris dataset’s simplicity makes it ideal for learning classification techniques and experimenting with different algorithms.
