# PowerBI project
## Purpose
This project allows the user to select two teams that the Power BI Report will then predict the score as if those two teams played each other. 
# Steps 
You will need Power BI Desktop to view this project
1. Select the NFL Prediction.pbix in this branch
2. Download the raw file and open it in Power BI Desktop
3. Select Team 1 and Team 2
# How it Works
Predictions are based on the average number of points Team 1 has against Team 2 for all seasons. It is then added to or subtracted by the relative standing of each team's history. The relative standing is found by subtracting the teams 2022 season average by their overall average.
In this way, we are finding the expected value for each team when against the other, while taking into account their relative standing overall.
Keep in mind, if teams are in different conferences, there will be little data for them playing against each other.
