# NBA Draft Combine Projection

This project analyzes historical NBA Combine data to build a predictive model for identifying lottery picks (top 14 selections) in the NBA Draft. By evaluating athletic measurements, performance metrics, and player statistics the project aims to provide data-driven insights into how combine results may influence draft position.

## Files
- `NBAproject.ipynb`: Contains all stages of data cleaning, feature selection, model training, and evaluation.

## Project Overview
- **Dataset**: Historical NBA Combine and game data including vertical leap, height, wingspan, points per game, assist per game, etc.
- **Target**: Binary classification — whether a player was selected as a lottery pick (Top 14) or not.
- **Objective**: Use combine and in-game performance metrics to predict the likelihood of lottery selection.

## Techniques & Tools
- Logistic Regression
- Pandas, NumPy, Seaborn, Matplotlib, Scipy.optimize

## Results
- A players points per game (PPG) was a strong predictor for lottery status.
- Model evaluation helped identify traits valued across draft classes.

## Goal
To support NBA front offices and draft analysts by quantifying how measurable combine results impact draft decisions.
