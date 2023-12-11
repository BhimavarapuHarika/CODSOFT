MOVIE RAATING PREDICTION(Task-1)

PROBLEM STATEMENT

The problem statement chosen for this project is to predict movie ratings with the help of machine learning models.

The dataset is taken from the Kaggle website, and it has a total of 15509 entries and 10 columns.

PROJECT SUMMARY

The project can be briefly summarized in the following steps:

•	Data Collection: Obtained a dataset containing historical movie data, including features like genre, director, actors, and ratings.

•	Data Cleaning and Exploration: Handled missing values in the dataset,Explored the dataset to understand its structure and characteristics.

•	Data Preprocessing: Converted year column to determine a datetime type,converted duration and votes columns into numeric and handled categorical variables like genre,director,actors using technique like target encoding.

•	Feature Engineering: Created a feature representing the average number of movies,average high rated genre,average high rated directors,average high rated actors.

•	Splitting the Data: Diving the dataset into trainin gand testing sets.this helps the model's performance on unseen data.

•	Building Model: We took a Linear Regression, RandomForestClassifier, DecisionTreeRegression and trained the model using training dataset.

•	Model Evaulation: We took Metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE),Mean Absolute Error(MAE) and r2_score(r^2).
