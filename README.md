# Car Insurance Claim Prediction


This repository contains a Jupyter Notebook that uses machine learning algorithms to predict whether a customer is likely to make a claim on their car insurance policy in the next 6 months.

# Dataset
The dataset used in this project contains information on policyholders, including attributes such as policy tenure, age of the car, age of the car owner, population density of the city, make and model of the car, power, engine type, and more. The target variable is a binary indicator that shows whether the policyholder filed a claim in the next 6 months or not.

# Approach
The notebook uses various machine learning algorithms to train and test the dataset. First, the data is preprocessed by checking for missing values, encoding categorical features, and normalizing numerical features. We performed upsampling as there were significant differences in the results. Then, several models are trained, including Logistic Regression, Random Forest, Decision Tree, KNN and Gradient Boosting. After training a voting classifier using Random Forest Classifier and Decision Tree Classifier, we used feature importance to select the most relevant columns. The top 10 importance columns were policy tenure, age of policyholder, age of car, population density, area cluster, model, displacement, engine type, gross weight, and volume. We then retrained the classifier to achieve better accuracy. The best model is chosen based on its accuracy, precision, and recall scores. 

# Results
After training and testing several models, the Voting Ensembles was found to be the most accurate, with an accuracy score of 0.99 on the test set.

# How to use
To use this notebook, simply download the dataset and open the Jupyter Notebook. Follow the instructions in the notebook to preprocess the data, train and test the models, and generate predictions.

# Future Work
In the future, this project could be expanded by including additional features, exploring more machine learning algorithms, and fine-tuning the hyperparameters of the existing models to improve their performance.
