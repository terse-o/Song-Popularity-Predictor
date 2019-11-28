Song Popularity Predictor using Spotify dataset

Language: R
Editor: RStudio (v1.2.1335)
Description: ML model created and trained on spotify dataset to predict if a song will be popular or
not depending on the several audio features of the song like acousticness, danceability, energy, etc.

NOTE:
Hello friends, I am writing this message to explain my motivation and approach towards building this project.
This was an academic project which I completed as part of the course Introduction to Data Mining and Machine
Learning. As part of the course, I learnt about different AI and ML models that are used for Data Mining. To
exercise the skill set I learnt, I had to implement them into a project. The whole course was also an introduction
to R language. I selected the Spotify dataset because I have been using the app to listen to music for quite
sometime and am actually impressed by their interface, predictive song suggestions and new playlists. I was
amazed to see how the app would devise new playlist suggestions based on my taste of music. I was sure that
they were using AI models to make such precise suggestions which I actually loved listening to. So I decided
to create something along the same lines.

I came across a spotify dataset on the kaggle repository (Link: https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db).
This dataset consisted of the audio features of the song along with the track information and it's popularity on a 
scale of 0 - 100. For the sake of my graduate college project, I filtered the data and deleted certain genres
which had less frequency to minimize processing time. I decided to categorize the top 25% of the songs as popular 
to discover the prominent features that make a song popular.

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