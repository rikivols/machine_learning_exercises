# Titanic - Machine Learning from Disaster

This is a Machine learning exercise from Kaggle, where we're trying to predict who survived the Titanic disaster.

https://www.kaggle.com/competitions/titanic

## Description

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

# The data
As we can see below, the data consists of multiple columns, such as passenger's cabin, name, gender, age, ticket, fare, etc.

## Output
Our task is to predict, whether that person survived or not. The output should be in this CSV format:
```
PassengerId,Survived
1000,0
1001,1
...
```