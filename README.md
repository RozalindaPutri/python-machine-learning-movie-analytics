🎬 Machine Learning Workflow in Movie Analytics using Python
📌 Project Overview

This project focuses on applying a machine learning workflow to movie analytics data. The main goal of this project is to predict whether a movie has a good rating or not based on several movie features.
The dataset used in this project consists of movie metadata and audience rating data. Several numerical features such as budget, popularity, and vote_average are selected as input features. The target variable is created from the rating column, where movies with ratings greater than or equal to 3 are categorized as good-rated movies.
Before building the machine learning model, the data goes through several steps, including selecting numerical data, separating features and target, splitting the data into training and testing sets, and scaling the features using MinMaxScaler. Two machine learning models are used in this project, namely K-Nearest Neighbors (KNN) and Decision Tree Classifier.

🎯 Objectives
Select numerical features from the movie dataset.
Separate input features and target variable.
Classify movies into good and not good rating categories.
Split the data into training and testing sets.
Apply feature scaling using MinMaxScaler.
Build machine learning models using KNN and Decision Tree.
Compare prediction results using crosstab evaluation.

📊 Key Features Used
budget
popularity
vote_average
rating

🤖 Machine Learning Workflow
Data selection using numerical columns.
Feature and target preparation.
Train-test split with a 70:30 ratio.
Feature scaling using MinMaxScaler.
Model training using KNN and Decision Tree.
Prediction on training and testing data.
Model evaluation using pandas crosstab.

🔍 Key Insights
Most movies in the dataset have ratings greater than or equal to 3.
The features used for prediction are budget, popularity, and vote_average.
The budget column has a much larger value range compared to other features, so scaling is needed.
Feature scaling helps balance the value range between features.
KNN and Decision Tree are used to predict movie rating categories.
The prediction results show that many movies are classified as good-rated movies.

💡 Recommendations
Data should be cleaned before being used in machine learning.
Feature selection is important because the selected features affect model performance.
Feature scaling is recommended when the features have very different value ranges.
KNN and Decision Tree can be used as basic models for movie rating classification.
Future projects can add more features such as runtime, revenue, profit, genre, or release_year.
Model evaluation can be improved using accuracy score, confusion matrix, and classification report.

🛠 Tools Used
Python
Pandas
Scikit-learn
Google Colab
CSV Dataset
Machine Learning
K-Nearest Neighbors
Decision Tree Classifier
MinMaxScaler

📂 Dataset
The dataset used in this project consists of:
movies_metadata.csv
Contains movie information such as budget, popularity, title, vote average, and other movie metadata.
ratings_small.csv
Contains audience rating data for movies.

📂 Project Deliverables
Machine learning workflow notebook
Data selection process
Feature and target preparation
Train-test split process
Feature scaling process
KNN classification model
Decision Tree classification model
Prediction result comparison
Project presentation for portfolio

📝 Notes
This project is created for learning and portfolio purposes. The main focus of this project is to understand how machine learning can be applied to movie analytics data, especially to predict whether a movie has a good rating or not.
Future improvements may include adding more features, trying other machine learning algorithms, and using more complete evaluation metrics to measure model performance more accurately.
