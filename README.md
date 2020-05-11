# Capstone_Project: Predicting market reaction and volatility based on daily news and technical indicators

## Background
This repository contains the notebook for project conducted as part of the data-science bootcamp.

## Description
The project attempts to evaluate and compare prediction capabilites of text (as represented by Top 25 daily worldnews headlines) and technical indicators (such as Stoch_%K, Stoch_%D, Momentum, and other) as applied to predicting the index price movement as well as its volatility. In a nutshell the four estimation attmepts include, predicting:

- price movement (up/same or down) by means of daily news
- price movement by means of technical indicators
- volatility (up/same or down) by means of daily news
- volatility by means of technical indicators.

![Project structure](https://github.com/DennisBuxmann/Capstone_Project/blob/master/images/project_structure1.jpg)

## Data
In this project the data provided by Aaron7sun and uploaded to [Kaggle](https://www.kaggle.com/aaron7sun/stocknews) has been used. In particular the data include two sets:
- News data: historical news headlines crawled from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single date.
(Range: 2008-06-08 to 2016-07-01)
- Stock data: Dow Jones Industrial Average (DJIA) is used to "prove the concept".
(Range: 2008-08-08 to 2016-07-01).

## Techniques used
`Python` `NumPy` `Pandas` `Sklearn` `Word2Vec` `RegEx` `beatifulsoup` `Maptplotlib` `Seaborn` `Random Forest` `XGBoost`

## Results

![Results](https://github.com/DennisB-KF/Capstone_Project/blob/master/images/Results.PNG)
## Future work
