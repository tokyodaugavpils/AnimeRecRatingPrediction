Anime Rating Predictor Project

⸻

Project Overview

This project builds a simple machine learning model that predicts the rating of an anime based on its genre, type, number of episodes, and popularity (number of members). We use a pre-merged dataset and follow a clear, step-by-step approach for data cleaning, feature extraction, model training, and evaluation.

⸻

Dataset

We use dataset "Anime Recommendations Database" by CooperUnion

    anime.csv

⸻

File Description

    animeprediction.ipynb

Anime Rating Predictor
	•	Loads the cleaned dataset
	•	Filters out missing genres and ratings
	•	Encodes genres (text like “Action, Fantasy”) into numbers
	•	Encodes anime type (TV, Movie, etc.)
	•	Handles missing or unknown episode counts
	•	Combines all features (genre + type + episodes + members) into one matrix
	•	Trains a RandomForestRegressor
	•	Evaluates performance using MSE (Mean Squared Error)
	•	Lets the user input the name of an anime and see:
	•	The predicted rating by the model
	•	The actual rating from the dataset

Goal: Predict anime ratings as accurately as possible and make it interactive by letting users test it with real anime names.
