# IPL Score Predictor

This Streamlit webapp enables user to predict total runs between teams using current runs and wickets.

**Algorithms used:**

* Linear Regression
* K-Nearest Neighbor Regressor 
* XGBoost Regressor
* RandomForest Regressor
* Decision Tree Regressor

**Hyperparamter Optimization:**

Used optuna for paramter optimization.

**Dataset:**

mid - match id
date - when matches are played
venue - place where matches aew played
bat_team - batting team
bowl_team - bowling team
batsman - batsman
bowler - bowler
runs - runs scored
wickets - wickets
overs - overs - next 3 are based on this
run_last_5 - runs scored in last 5 overs
wicket_last_5 - wickets in last 5 overs
stricker - batsman playing as main 1
non-striker - batsman playing as runner up - not main 0
total - total score (target variable)

The dataset comprises of over by over details of matches and runs from 2008 to 2020.

Dataset link: https://github.com/Chitwan54/IPL-Score-Prediction/blob/main/ipl_data.csv

**Streamlit App:**

![](https://github.com/zep-analytics/IPLScorePredictor/blob/main/streamlit_app/ipl_score_predictor.gif)
