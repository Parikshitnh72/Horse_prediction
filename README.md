#Horse Race Prediction

![image](https://github.com/Parikshitnh72/Horse_prediction/assets/153513327/8c4b2743-0f43-4129-9dd0-0d7a3f7de3a4)










Problem Statement
![image](https://github.com/Parikshitnh72/Horse_prediction/assets/153513327/76c0fd83-e5e0-4fc2-b82b-ed8e437702fb)






Data Sources
Executive Summary
Data Dictionary
Recommendations
Conclusion

#Background

Horse racing has a long and distinguished history, practised in civilisations across the world since ancient times. The modern horse racing became well-established in the 18th century in Britian. It continued to grow in popularity till this day, and was one of the few sports that continued during the Covid-19 crisis in Australia and Hong Kong.

Horse racing is the most important sport in Hong Kong. With only 24 trainers and a similar number of jockeys, participants are firmly in the spotlight. The regulation and governance of the horse racing industry comes under the supervision of the Hong Kong Jockey Club.

#Problem Statement
Punters have access to information available on the HKJC website, with veterinary and trackwork record available at the click of a button. There are many factors that could affect the race result and millions have tried to find a winning formula in order to make a profit from betting. We did a simple test to see what would happen if we had bet $1 on every horse with the lowest odds. Theoretically, this should work since the horse with the lowest odds tends to be the favourite. Our results showed otherwise.

BetLowest

And so the problem we want to address here is:

Can we use machine learning to make predictions to profit from horse races?

We will follow the data science process to answer this problem.

Define the problem
Gather & clean the data
Explore the data
Model the data
Evaluate the model
Answer the problem

#Data Sources
The dataset contains the race result of 1561 local races throughout Hong Kong racing seasons 2014-17. They can be downloaded from Kaggle at this link.

The data dictionary will be provided at the bottom of this file.

Executive Summary
#INTRODUCTION

This project seeks to make predictions on the outcome of horse races through both classification and regression models. For classification models, we aim to predict the winner and top 3 positions of a race. For regression models, we aim to predict the finish time of the horses, hereby predicting the winner of the race.

With the prediction results, we will make bets using different strategies to profit from the horse race. Backtesting results of each model will also show the number of bets and profit made from each strategy.

#METHODOLOGY

The work was done in 6 seperate notebooks.

Preprocessing - Cleaning and tidying of data, Feature Engineering
EDA - Data visualisation and analysis of key patterns
Classification Modelling - Training dataset fitted on 4 models to get classfication predictions
Regression Modelling - Testing dataset fitted on 4 models to get regression predictions
Backtesting - Using betting strategy to answer the problem statement of whether we can profit from horse races
Deployment - To build an application using Tableau
The application was deployed on Tableau and can be accessed. 
![image](https://github.com/Parikshitnh72/Horse_prediction/assets/153513327/e5e722e7-9dc7-479d-999e-5cf43ca3b199)

