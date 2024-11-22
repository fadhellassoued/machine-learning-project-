# Project Overview
This project focuses on using machine learning models to predict the outcomes of Premier League football matches. The primary objective is to determine whether the home team will win, or if the match will result in a draw or an away win. This involves exploratory data analysis, feature engineering, and model evaluation to build a robust predictive system.

## Project Goals
- **Data Understanding**:  
  Analyze match data to uncover trends and relationships that impact match outcomes.  

- **Feature Engineering**:  
  Extract meaningful features from raw match data, such as team form, home/away statistics, and head-to-head records.  

- **Model Building**:  
  Compare multiple classification models, including RandomForestClassifier and XGBoost.  

- **Evaluation**:  
  Use metrics like accuracy, precision, recall, F1-score, and confusion matrices to assess model performance.


# Dataset
Source: [Football-Data.co.uk](https://www.football-data.co.uk/)

some features in the dataset:
- **Match Information**:  
  - `Div`: League Division  
  - `Date`: Match Date (dd/mm/yy)  
  - `Time`: Time of match kick-off  

- **Teams and Results**:  
  - `HomeTeam`: Home Team  
  - `AwayTeam`: Away Team  
  - `FTHG` and `HG`: Full Time Home Team Goals  
  - `FTAG` and `AG`: Full Time Away Team Goals  
  - `FTR` and `Res`: Full Time Result (`H` = Home Win, `D` = Draw, `A` = Away Win)  
  - `HTHG`: Half Time Home Team Goals  
  - `HTAG`: Half Time Away Team Goals  
  - `HTR`: Half Time Result (`H` = Home Win, `D` = Draw, `A` = Away Win)  
  - `Referee`: Match Referee  

- **Performance Statistics**:  
  - `HS`: Home Team Shots  
  - `AS`: Away Team Shots  
  - `HST`: Home Team Shots on Target  
  - `AST`: Away Team Shots on Target  
  - `HC`: Home Team Corners  
  - `AC`: Away Team Corners  
  - `HF`: Home Team Fouls Committed  
  - `AF`: Away Team Fouls Committed  
  - `HO`: Home Team Offsides  
  - `AO`: Away Team Offsides  
  - `HY`: Home Team Yellow Cards  
  - `AY`: Away Team Yellow Cards  
  - `HR`: Home Team Red Cards  
  - `AR`: Away Team Red Cards  

- **Betting Odds**:  
  - `B365H`: Bet365 home win odds  
  - `BWH`: Bet&Win home win odds  
  - `PSH`: Pinnacle home win odds  
  - `WHH`: William Hill home win odds  
