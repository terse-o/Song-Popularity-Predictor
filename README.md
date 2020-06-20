Song Popularity Predictor using Spotify dataset

Language: R
Editor: RStudio (v1.2.1335)
Description: ML model created and trained on spotify dataset to predict if a song will be popular or
not depending on the several audio features of the song like acousticness, danceability, energy, etc.

NOTE:
I came across a spotify dataset on the kaggle repository (Link: https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db).
This dataset consisted of the audio features of the song along with the track information and it's popularity on a scale of 0 - 100. 
I filtered data (Informatica Cloud) and scrapped certain genres which had greater standard deviation to minimize processing time. 
I decided to categorize the top 25% of the songs as popular to discover the prominent features that make a song popular.

To discribe my entire project and the flow of the code I also created a video that is uploaded on Youtube.
Link: https://www.youtube.com/watch?v=LSDF96Ra9tk&feature=youtu.be

Basic packages used in the project are ggplot2, caret, reshape, psych, caretEnsemble, e1071, kernlab, naivebayes,
C50, randomForest, pROC.
Models: Logistic Regression (backfitted), Naive Bayes, Decision Tree, Random Forest, Ensemble Model

OVERVIEW:
-Data Acquisition and EDA

-Data Exploration
-Cleaning & Shaping
-Model Construction
-Evaluation of Models
-Optimum Features for Popular Songs
