# spotify-song-popularity-prediction
Machine learning project that predicts song popularity using Spotify data.



Project Overview

This project applies machine learning techniques to analyze Spotify song data and predict whether a track is likely to become popular. The workflow includes data preprocessing, feature engineering, model training, and evaluation using Python data science tools.

The goal of the project is to understand how musical features such as tempo, loudness, energy, and danceability influence song popularity.

Technologies Used:
  Python
  Pandas
  NumPy
  Scikit-learn
  CatBoost
  Matplotlib
  Seaborn


Project Steps:
1. Data Cleaning
  - Removed unnecessary columns
  - Handled missing values
  - Removed duplicate records

2. Feature Engineering
  - Converted categorical variables using dummy encoding
  - Extracted useful features from the dataset

3. Model Training
  - Split the dataset into training and testing sets
  - Trained a CatBoostClassifier model

4. Model Evaluation
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix visualization


Goal
The project demonstrates how machine learning models can be used to identify patterns in music data and predict song popularity.


Dataset
- Spotify dataset containing song attributes such as:
- danceability
- energy
- tempo
- loudness
- valence
- duration
- language
- genre
