# football-match-score-prediction
Machine learning project exploring football score prediction using in-match performance metrics and Linear Regression.

# Predicting Football Match Score Using In-Match Performance Matrix

A machine learning project exploring how in-match performance metrics can be used to predict football match scores using Linear Regression.

## Project Objective

The objective is to identify important in-match performance metrics and develop a model that can predict the expected final score.

The dataset contains full-time match statistics rather than live or halftime statistics. Therefore, the project serves as a proof of concept for how the same approach could be extended to real-time score prediction using live match data.

## Methodology

- Dataset extraction
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature and correlation analysis
- Linear Regression model building
- Testing multiple feature combinations
- Feature reduction
- Final model development
- Final score prediction program

## Final Model

The final model uses four performance metrics:

- Shots on Goal – Home Team
- Shots on Goal – Away Team
- Goalkeeper Saves – Home Team
- Goalkeeper Saves – Away Team

Multiple feature combinations were tested, and the final model was selected based on the R² score.

## Final Prediction Program

The program takes the four selected in-match metrics as input and predicts the expected match score.

An Argentina vs Egypt FIFA World Cup 2026 example was used to demonstrate the final prediction program.

## Project Limitation

The dataset contains full-time statistics, so the current model is not a true live prediction system. With live or halftime statistics, the same methodology could be extended toward real-time score prediction.

## Project Files

- `Football_Score_Regression.ipynb` — Complete Jupyter Notebook containing the analysis, visualizations, model building and final prediction program.
- `Football_Score_Prediction.pptx` — Project presentation.
