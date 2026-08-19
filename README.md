# Disease Surge Predictor

A full-stack web application that predicts short-term disease outbreak 
risk in Uttar Pradesh using statistical modeling and machine learning.

## What it does (planned)
Ingests public health data (case counts, weather, AQI) for regions in 
Uttar Pradesh, fits probability distributions to model disease case 
behavior, and forecasts near-term surges with calibrated confidence 
intervals — e.g., "72% chance dengue cases exceed 50 in the next 7 days."

## Why it's different
Most forecasting projects report accuracy and stop. This project tracks 
prediction calibration over time — comparing predicted probabilities 
against actual outcomes — so the model's confidence can be trusted, not 
just its accuracy.

## Tech stack
- **Backend:** Java (Spring Boot) — API, database, core app logic
- **ML/Stats microservice:** Python (scipy.stats, statsmodels, scikit-learn/XGBoost)
- **Frontend:** React
- **Database:** PostgreSQL

## Status
🚧 In early development. See `docs/LEARNING_LOG.md` for build progress.

## Setup
_Instructions coming soon as the project takes shape._
