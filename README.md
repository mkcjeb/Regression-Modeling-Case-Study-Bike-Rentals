# Regression Modeling Case Study (Kaggle Competition)
To develop a machine learning model that predicts the daily bike rentals and gives insights into the factors influencing bike rental demand.

## Disclaimer
I accidentally deleted my original account on Kaggle and am unable to retrieve it that's why the user name is deleted in the snip. :(

## Private Leaderboard Results
![Regression Case Study Kaggle](https://github.com/mkcjbantugon/Regression-Modeling-Case-Study/assets/157083966/adc87f99-91ba-44a5-b89a-8526bb8ea2d0)

## Public Leaderboard Results
![Public Leaderboard Kaggle](https://github.com/mkcjbantugon/Regression-Modeling-Case-Study/assets/157083966/556d78f3-12de-4572-a830-d25b6262d0f6)

## Objective
The bike sharing industry has grown tremendously in recent years, with an estimated global value of $2.8 billion in 2023. This is due to a number of factors, such as convenience, sustainability, and physical fitness. As a result of the market's growth, your client, a major city in the United States, has tasked you with developing a machine learning model to predict the number of bike rentals on a given day, as well as to provide insights into the factors that contribute to bike rental demand.

## Your Client
The Cook County Planning and Development Department, responsible for the Chicago metropolitan area in the United States.

## Requirement
You must have Python installed in your computer in order to run the code.

Download the jupyter notebook file "Bantugon_Michelle_Complete Analysis.ipynb" (2.23 MB) to your computer. Run your terminal window to access jupyter notebook and go to the folder where you save the file and run.

Save the train and test files in the same repository as the Jupyter notebook to prevent any problems with importing and loading them.

## Analysis

<b>Factors Affeting Bike Rentals</b>

<b>Hourly Trends</b>: Rentals peak during morning (<b>8 am</b>) and evening rush hours (<b>5 pm and 6 pm </b>), indicating commuter usage. Early morning and late night hours (1 am to 3 am) have the lowest rentals.

<b>Weekday Trends</b>: <b>Saturday</b> see higher rentals than weekdays, with Sunday also showing increased demand compared to weekdays. Wednesday tend to have slightly higher rentals.

<b>Weather Impact</b>: <b>Higher temperatures</b> (specifically if bike sharing system is active) positively affect rentals, while humidity negatively influences demand. <b>Dew point temperature</b> has a positive impact, indicating comfort levels may influence rentals.

<b>Precipitation and Wind</b>: Precipitation has a <b>negative impact on rentals</b>, as indicated by the negative coefficient. Wind speed  also negatively affects rentals, although to a lesser extent.

<b>Holiday Effect</b>: Holidays see <b>decreased rentals</b>, likely due to non-working day status, impacting commuter patterns.

<b>Heat Index</b>: The positive coefficient for heat index suggests a <b>positive influence on rentals</b>, possibly indicating a preference for biking in warmer weather.


## Credits


* Licence badge from [Shields.IO](https://shields.io/)
* Kaggle Competition hosted by Professor Chase Kusterer.
  https://www.kaggle.com/competitions/computational-data-analytics-fy-spring-2024/leaderboard
