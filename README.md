# Seattle-Emergency-Response
Predicting Emergency Response Outcomes Using Seattle’s CAD Data

## Overview
This notebook was created as a part of my final project for EDUC 244: Data Mining and Analytics at UC Berkeley. In this project, my team and I choose to analyze Seattle's Emergency Response Dataset with the goal of creating accurate prediction models. I was responsible for creating a model that would best predict response time. 

My goals in this project were two-fold: 
1. Feature Engineering & Importance: Determining which factors (e.g., location, time of day) are the strongest drivers of response times.
2. Model Selection: Identifying the most effective predictive model through rigorous testing on historical data.

I chose these goals as I hoped that my analysis and models would ultimately help uncover "blindspots" in the system, and improve overall transparency in the current emergency response system for operators and citizens alike.

TLDR. I found that geographic indicators like latitude and longitude were decent predictors of response time, indicating some variance in coverage/availbility depending on neighbourhood. Additionally, I found that RF was the best model for predicting outcomes. (As this was an assignment, I was operating under limited resources, I think there are improvements that can be made with feature engineering/additional models.)
