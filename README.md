![](https://www.ieyenews.com/wp-content/uploads/2022/02/MIT-IDSS-LOGO-Mailer-02-1.jpg)

# MIT IDSS Data Science and Machine Learning: Making Data-Driven Decisions Program - Academic Hackathon - Shinkansen Bullet Train
## Solution by Oscar Suarez Lechado - o@oszl.xyz
## 12th Nov. 2022



## OBJECTIVE: Predict whether a passenger was satisfied or not considering his/her overall experience of traveling on the Shinkansen Bullet Train

This problem aims to determine the relative importance of each parameter of the provided data regarding their contribution to the passenger's overall travel experience.

The on-time performance of the trains along with passenger information is published in a file. These passengers were later asked to provide their feedback on various parameters related to the travel along with their overall experience. These collected details are made available in the survey report.

In the survey, each passenger was explicitly asked whether they were satisfied with their overall travel experience or not, and that is captured in the data of the survey report under the variable labeled ‘Overall_Experience’.

The objective of this problem is to understand which parameters play an important role in swaying passenger feedback towards a positive scale.


## Main Idea

Based on exploratory analysis of the data, exploratory model testing, and previous experience; an XGBoost model was selected to solve this challenge. In that exploratory phase, the logic behind feature engineering/transformation was addressed. Also, other models were used to validate the relative importance of the features.

The posted notebook will reflect these transformations and analysis-based decisions. However, the focus will be to show the training and hyperparameter tuning of the XGB model. I plan to upload the data analysis as well.

