![@neonbrand via Unsplash - person holding space gray iPhone 6](https://images.unsplash.com/photo-1495434942214-9b525bba74e9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80)

# Spotify Analysis

This repository contains a comprehensive analysis of Spotify data, focusing on preprocessing, modeling, and evaluation to uncover insights and build predictive models. The project leverages Python and popular machine learning libraries to predict and analyze trends in music playlists.

---

## Overview

The project analyzes Spotify playlist data to explore trends and build predictive models. It involves extensive data preprocessing, feature engineering, and machine learning. The ultimate goal is to understand the data’s patterns and predict playlist trends using various models.

---
## Dataset

The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs?select=spotify_songs.csv). It contains 30,000 Spotify songs with features such as track names, artists, and various audio characteristics. 

The dataset file, `spotify_songs.csv`, has been used as the basis for preprocessing, analysis, and modeling in this project. For more details about the dataset, you can visit the [Kaggle page](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs?select=spotify_songs.csv).

---

## Features

- **Data Preprocessing**:
  - Handling missing values.
  - Feature engineering, such as extracting the release year from dates.
  - Dropping irrelevant columns like track IDs and playlist names.

- **Machine Learning Models**:
  - Ridge Regression
  - Stochastic Gradient Descent (SGD) Regressor
  - Random Forest Regressor (final selected model).

- **Hyperparameter Tuning**:
  - Optimized models using `RandomizedSearchCV`.

- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - \(R^2\) Score

---

## Installation

To run this project locally, follow these steps:


### Clone the repository
git clone https://github.com/TuvshinSelenge/spotify_analysis.git

### Navigate to the project directory
cd spotify_analysis

### Create a virtual environment (optional but recommended)
python -m venv env

### Activate the virtual environment
### On macOS/Linux:
source env/bin/activate
### On Windows:
env\Scripts\activate

### Install the required dependencies
pip install -r requirements.txt

## Technologies Used

	•	Python: Core programming language.
	•	scikit-learn: Machine learning library for preprocessing, modeling, and evaluation.
	•	pandas: Data manipulation and analysis.
	•	matplotlib & seaborn: Data visualization.
	•	NumPy: Numerical computations.
