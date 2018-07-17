# Capstone: Predicting the FIFA World Cup 2018 Winner

**by Awab Idris**
---

**Table of Contents**

  num | File
----- | ------------
**1** | _Datasets_
**2** | _Capstone Notebook_
**3** | _readme.md_
**4** | _Presentation_
## Datasets:

[FIFA World Cup 2018 fixures](https://www.kaggle.com/lekroll/fifa-worldcup-2018-matches) I used this dataset to get the world cup 2018 matches for predictions.

[All previous world cup matches](https://www.kaggle.com/abecklas/fifa-world-cup#WorldCupMatches.csv) I used this dataset for training my model. 

[FIFA World Cups winners](https://www.kaggle.com/abecklas/fifa-world-cup#WorldCups.csv) For visualization purposes.

## Problem Statement:

the purpose of this project is to build a multiclassification model that predicts the winner of the soccer world cup based on the previous matches for the world cup, I will evalute the model by the accuracy metric.

## Summary:

For this project I trained my model on the previous world cup matches from 1930 to 2014 in order to predict the world cup winner in 2018. I started by cleaning the data and perform intensive EDA followed by feature engineering.

For the modeling part I applied multiclassifaction models to predict which team is going to win each match, so it's either the home team wins or the away team wins or draw. The best models were **LogisticRegression**, **AdaBoostClassifier** and **XGBClassifier**, so I went with the best model which had the best score **AdaBoostClassifier**.

The prediction process consisted on six prediction parts:

1- Group stages matches.

2- Round of 16 matches.

3- Quarter final matches.

4- Semi final matches.

5- Third place match.

6- Final match.

Each round is based on the prior round, so I had to predict the group stages matches first to determine which team is going to qualify to the next round.

## Results:

1- **Brazil** won the FIFA World Cup 2018.

2- **Germany** won the second place.

3- **Denmark** won the third place.

4- **France** came on the fourth place.

