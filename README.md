# predicting_fpts
This repository contains code that transforms a dataset from Underdog Fantasy using Pandas and then trains and tests an XGBoost model with hyperparameter tuning on the transformed dataset. The tabular data (in form of csv files) used in the code is provided as well.

'BBM_II_Data_Dump_Regular_Season_01312022.csv' was downloaded directly from: https://underdognetwork.com/football/best-ball-mania-ii-downloadable-pick-by-pick-data. The dataset includes information from every single pick that was made during Underdog's Best Ball Mania II contest during the 2021-2022 NFL season.

'2021players.csv' contains every player who was active during the 2021 NFL season and the team that they played for that season. It is a modified version of the Pro-Football-Reference 2021 NFL Fantasy Rankings page found here: https://www.pro-football-reference.com/years/2021/fantasy.htm. A few changes and additions to the data were made manually to ensure the data is accurate and inclusive of every player drafted in Best Ball Mania II.
