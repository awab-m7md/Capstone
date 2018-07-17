# Capstone: Predicting the FIFA World Cup 2018 Winner

**by Awab Idris**
---

**Table of Contents**

  num | File
----- | ------------
**1** | _Datasets_
**2** | _Capstone Notebook_
**3** | _readme.md_

## Datasets:

[FIFA World Cup 2018 fixures](https://www.kaggle.com/lekroll/fifa-worldcup-2018-matches) I used this dataset to get the world cup 2018 matches for predictions.
[All previous world cup matches](https://www.kaggle.com/abecklas/fifa-world-cup#WorldCupMatches.csv) I used this dataset for training my model. 
[FIFA World Cups winners](https://www.kaggle.com/abecklas/fifa-world-cup#WorldCups.csv) For visualization purposes.

## Problem Statement:

the purpose of this project is to build a multiclassification model that predicts the winner of the soccer world cup based on the previous matches for the world cup, I will evalute the model by the accuracy metric.

## Summary:

For this project I trained my model on the previous world cup matches from 1930 to 2014 in order to predict the world cup winner in 2018. I started by cleaning the data and perform intensive EDA followed by feature engineering.

For the modeling part I applied multiclassifaction models to predict which team is going to win each match, so it's either the home team wins or the away team wing or draw. The best models were **LogisticRegression**, **AdaBoostClassifier** and **XGBClassifier**, so I went with the best model which had the best score **AdaBoostClassifier**.

The prediction process consisted on six parts:
1- Predicting the group stages matches.
2- Predictiong round of 16 matches.
3- Predicting quarter final matches.
4- Predicting semi final matches.
5- Predicting third place match.
6- Predicting the final match.

Each round is based on the prior round, so I had to predict the group stages matches first to determine which team is going to qualify to the next round.

## Results:

1- **Brazil** won the World Cup 2018.
2- **Germany** won the second place.
3- **Denmark** won the third place.
4- **France** came on the fourth place.

