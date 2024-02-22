# Predict-Ticket-Price
## Introduction
This project is based on the titanic shipwreck dataset. The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

## Objective
Build a regression model to predict ticket price(Fare)

## Methodology
### Data Preparation
Create new features through feature engineering; Deal with missing values; Clean up data, ie. strip extra white spaces in string values. There is focus on dealing with missing data in this project.

#### Dealing With Missing Data
This demonstrates filling with mean, mode and estimate from other columns.

## Feature Engineering
This part creates a new column called FamilySize. There are 2 columns related to family size, parch indicates parent or children number, Sibsp indicates sibling and spouse number.
Take one name 'Asplund' as example, the data shows that total family size is 7(Parch + SibSp + 1), and each family member has same Fare, which means the Fare is for the whole group. So family size will be an important feature to predict Fare.

## Modeling
With modeling, a classification is done on Survived to predict whether a passenger could survive the disaster or a regression on Fare to predict ticket fare. A linear regression on Fare is constructed where it chooses Pclass, Embarked, FamilySize as independent variables. 

##### This is a concise summary of activities carried out in the project.

## Appreciation
I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about [Azubi Africa here](https://medium.com/@azubiafrica) and take a few minutes to visit this link to learn more about Azubi Africa life-changing [programs](https://bit.ly/41CGCwK)

## Tags
[Azubi Data Science](https://bit.ly/3ARq742)