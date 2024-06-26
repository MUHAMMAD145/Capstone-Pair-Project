# Capstone-Pair-Project

![image](https://github.com/MUHAMMAD145/Capstone-Pair-Project/assets/72031646/ea03c2d4-100d-4da1-a754-782470c8b822)

# Project Title: IPL Score Predictor

**Project Introduction:** The IPL Score Predictor project aims to develop a machine learning model that accurately predicts the total score of ongoing Indian Premier League (IPL) cricket matches in real-time. 

# Project Details

**Input Data:** The application will take various statistics and details of the current IPL match as input to make predictions. These inputs include:
  - **Batting Team:** Selection of the team currently at bat.
  - **Bowling Team:** Selection of the opposing bowling team.
  - **Current Over:** The over currently in progress.
  - **Current Runs:** The number of runs scored up to the current over.
  - **Wickets Taken:** The number of wickets fallen up to the current over.
  - **Runs in Last 5 Overs:** Runs scored in the last 5 overs.
  - **Wickets in Last 5 Overs:** Wickets taken in the last 5 overs.

**Machine Learning Model:** We will develop and train a machine learning model using historical IPL match data. This model will learn to analyze the provided inputs and predict the total score a team is likely to achieve by the end of the innings.

# Dataset

**Dataset:** The dataset comprises of over by over details of matches and runs from 2008 to 2020.

**Dataset Used:** ipl_data.csv

  - mid - match id
  - date - when matches are played
  - venue - place where matches aew played
  - bat_team - batting team
  - bowl_team - bowling team
  - batsman - batsman
  - bowler - bowler
  - runs - runs scored
  - wickets - wickets
  - overs - overs - next 3 are based on this
  - run_last_5 - runs scored in last 5 overs
  - wicket_last_5 - wickets in last 5 overs
  - stricker - batsman playing as main 1
  - non-striker - batsman playing as runner up - not main 0
  - total - total score (target variable)


# Machine Learning Algorithms

  - Linear Regression
  - K-Nearest Neighbor Regressor
  - XGBoost Regressor
  - RandomForest Regressor
  - SVR
  - Decision Tree Regressor
    



