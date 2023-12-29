MOVIE RAATING PREDICTION(Task-1)

PROBLEM STATEMENT

The problem statement chosen for this project is to predict movie ratings with the help of machine learning models.

The dataset is taken from the Kaggle website, and it has a total of 15509 entries and 10 columns.

PROJECT SUMMARY

The project can be briefly summarized in the following steps:

•	Data Collection: Obtained a dataset containing historical movie data, including features like genre, director, actors, and ratings.

•	Data Cleaning and Exploration: Handled missing values in the dataset and explored the dataset to understand its structure and characteristics.

•	Data Preprocessing: Converted year column to determine a DateTime type, converted duration, and votes columns into numeric, and handled categorical variables like genre, director, and actors using techniques like target encoding.

•	Feature Engineering: Created a feature representing the average number of movies, average high-rated genre, average high-rated directors, and average high-rated actors.

•	Splitting the Data: Diving the dataset into training and testing sets. this helps the model's performance on unseen data.

•	Building Model: We took a Linear Regression, RandomForestClassifier, and DecisionTreeRegression and trained the model using a training dataset.

•	Model Evaluation: We took Metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error(MAE) and r2_score(r^2).

RESULT

The RandomForestRegressor performed a greater accuracy of 80% compared to other models
