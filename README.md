# NBA_Player_analysis

GOAL
-Use anthtropometrics and past box-score performances to predict outcomes in match ups. 
	-Ideal precision to have inference on Sports betting

EXECUTION

-One approach is using multiple predictors to determine a linear regression model that predicts an over or under a given threshold. Predictors can include; Matchup box scores and anthropometrics(could be averaged for potential matchups weighted for likelihood of matchup), Non-quantifiables e.g. Head Space(Based on: recent occurences(Child birth, family drama), Injury, History with opponent(Drama)), Recent Form (Check final Case Study in STAT206, for execution in R), (The customer churn problem in TIM 147 is a good resource as well).

-Another approach would be using Random Forest where different attributes are used to predict different outcomes and then averaged

-Another approach could be using the KNN model to classify them into a over or under

-Can also use naive bayes as a model which would return the most likely class(over,under) given the different predictors

 