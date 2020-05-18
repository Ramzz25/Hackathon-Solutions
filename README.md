# Hackathon-Solutions
This repo contains code for the analytics competition that I have participated in.

## List of Hackathons (till now) : 

### 1. Astro Analytics TechSoc Event IITM

PS : We have been given the real and simulated values of co-ordinates and velocities of various satellites. The readings were taken over a course of 30 days. We have to predict the real co-ordinates and velocities of the satellites given the time and simulated values.

Link : https://www.kaggle.com/c/astro-analytics-techsoc-iitm/overview

My approach : I have predicted the co-ordinates and velocities of the satellites using KNN (k-nearest neighbours) Regression.

Private LeaderBoard : 13 <br>
Public LeaderBoard : 18

### 2. Flipr Hackathon 4.0

PS: Given several info. about a person, predict the probability that he will be infected by the COVID-19 virus.

My Approach : I have tried implementing various conventional ML algorithms and Neural Network to predict the probability and then used the best-one (based on MSE) for the final prediction.

Private LeaderBoard : NA <br>
Public LeaderBoard : NA

### 3. JanataHack - E-Commerce Analytics ML Hackathon (Hosted in Analytics Vidhya)

PS : Given the time in which the user logs in & out and a list of products and its categories, we have to predict the gender of the user.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-e-commerce-analytics-ml-hackathon/

My Approach : I used the data from 'productList' column to capture the frequencies of the different categories a user visits in his/her session, and then used PCA to reduce the dimensionality of the features. Finally, used RandomForest and XGBoost for classification.

Private LeaderBoard : 42 <br>
Public LeaderBoard : 101

### 4. JanataHack - NLP Hackathon (Hosted in Analytics Vidhya)

PS : Given a user's review about a game and the game's description, we have to predict if the user is recommending the game or not.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-nlp-hackathon/

My Approach : First cleaned the user reviews using general preprocessing NLP techniques like stopwords removal and lemmentization of the words. Then used BERT encoder to extract features from the sentence, but using a simple TF-IDF vectorizer for feature extraction yielded better results.

Edit 1 : Doing Transfer Learning on a pre-trained DistilRoBERTa (light-weight version of facebook's RoBERTa) model showed improved results (F1 score - 0.9). The results can be improved further by using the original RoBERTa model instead of distiled one.

Private LeaderBoard : 120 <br>
Public LeaderBoard : 111

### 5. JanataHack - Time Series Forecasting Hackathon (Hosted in Analytics Vidhya)

PS : Given electrical consumption for first 23 days of a month, we have to predict the consumption for rest of the days of the month for 5 years.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-time-series-forecasting/

My Approach : Used lagged features of the Target variable as new features and used an ensemble of SVM and kNN.

Private LeaderBoard : 121 <br>
Public LeaderBoard : 1

### 6. JanataHack - HR analytics Hackathon (Hosted in Analytics Vidhya)

PS : Given various features like geography, educational status, we have to predict if a individual would want to pursue a career in the field he has taken a skill development course in.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-hr-analytics

My Approach : Used KNN method to impute missing values and used an ensemble of various boosting algorithms for final prediction.

Private LeaderBoard : 26 <br>
Public LeaderBoard : 34

### 7. JanataHack - Mobility analytics Hackathon (Hosted in Analytics Vidhya)

PS : Given various features about a cab customer, we have to classify him into 3 categories.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-mobility-analytics/

My Approach : Used Iterative method to impute missing numerical values and used an Voting Classifier of 3 boosting algorithms for final prediction.

Private LeaderBoard : 21 <br>
Public LeaderBoard : 41