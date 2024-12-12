# Spotify Analysis

Spotify Analysis

This repository contains a comprehensive analysis of Spotify data, focusing on preprocessing, modeling, and evaluation to uncover insights and build predictive models. The project uses Python and popular machine learning libraries to predict and analyze trends in music playlists.

Overview

The project analyzes Spotify playlist data to explore trends and build predictive models. It involves extensive data preprocessing, feature engineering, and machine learning. The ultimate goal is to understand the data’s patterns and predict playlist trends using various models.

Features

	•	Data Preprocessing:
			Handling missing values.
			Feature engineering, such as extracting release year from dates.
			Dropping irrelevant columns like track IDs and playlist names.
	•	Machine Learning Models:
			Ridge Regression
			Stochastic Gradient Descent (SGD) Regressor
			Random Forest Regressor (final selected model).
	•	Hyperparameter Tuning:
			Optimized models using RandomizedSearchCV.
	•	Evaluation Metrics:
			Mean Squared Error (MSE)
			Mean Absolute Error (MAE)
			R² Score

Installation

To run this project locally, follow these steps:
1. Clone the repository: git clone https://github.com/TuvshinSelenge/spotify_analysis.git
2. Navigate to the project directory: cd spotify_analysis
3. Create a virtual environment (optional but recommended): python -m venv env source env/bin/activate   # On Windows: env\Scripts\activate
4. Install the required dependencies: pip install -r requirements.txt

Technologies Used

	•	Python: Core programming language.
	•	scikit-learn: Machine learning library for preprocessing, modeling, and evaluation.
	•	pandas: Data manipulation and analysis.
	•	matplotlib & seaborn: Data visualization.
	•	NumPy: Numerical computations.
