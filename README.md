NAME :Marthati Vignesh

COMPANY :CODTECH IT SOLUTIONS

ID :CT4AI4631

Domaine :ARTIFICAL INTELLIGENCE

Duration :10th JULY 2024 to 10th AUG 2024

Mentor :G.SRAVANI



##Overview of the Project: This project demonstrates the process of training and evaluating three different machine learning models using the Iris dataset. The primary objective is to compare the performance of Logistic Regression, Decision Tree, and Random Forest classifiers in predicting the species of iris flowers.

Data Loading:

The Iris dataset is loaded from sklearn's datasets module. The dataset includes features such as sepal length, sepal width, petal length, and petal width, along with the target variable representing the species of the iris flowers. Data Splitting:

The dataset is split into training and testing sets using train_test_split with an 80-20 split to ensure that the models are trained and evaluated on different data. Model Initialization and Training:

Three models are initialized: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier. Each model is trained on the training data. Model Predictions:

After training, each model makes predictions on the test set to evaluate its performance. Model Evaluation:

A custom function is defined to evaluate each model's performance using four metrics: accuracy, precision, recall, and F1-score, all calculated with a 'weighted' average to account for class imbalances. The function prints these metrics for each model, allowing for a comparison of their effectiveness in classifying the iris species.
