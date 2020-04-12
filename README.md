# Hackathon-Solutions
This repo contains code for the analytics competition that I have participated in.

## List of Hackathons (till now) : 

### 1. Astro Analytics TechSoc Event IITM

PS : We have been given the real and simulated values of co-ordinates and velocities of various satellites. The readings were taken over a course of 30 days. We have to predict the real co-ordinates and velocities of the satellites given the time and simulated values.

Link : https://www.kaggle.com/c/astro-analytics-techsoc-iitm/overview

My approach : I have predicted the co-ordinates and velocities of the satellites using KNN (k-nearest neighbours) Regression.

### 2. Flipr Hackathon 4.0

PS: Given several info. about a person, predict the probability that he will be infected by the COVID-19 virus.

My Approach : I have tried implementing various conventional ML algorithms and Neural Network to predict the probability and then used the best-one (based on MSE) for the final prediction.

### 3. JanataHack - E-Commerce Analytics ML Hackathon (Hosted in Analytics Vidhya)

PS : Given the time in which the user logs in & out and a list of products and its categories, we have to predict the gender of the user.

Link : https://datahack.analyticsvidhya.com/contest/janatahack-e-commerce-analytics-ml-hackathon/#ProblemStatement

My Approach : I used the function *CountVectoriser* to capture the frequencies of the different categories a user visits in his/her session, and then used PCA to reduce the dimensionality of the features. Finally, used RandomForest and XGBoost for classification.
