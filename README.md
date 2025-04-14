# 🏡 California Housing Price Prediction

This project uses the California Housing dataset to predict **median house values** based on demographic and geographic features. It demonstrates data analysis, visualization, and machine learning techniques using Python.

## 📦 Dataset

- Loaded from `sklearn.datasets.fetch_california_housing`
- 20,640 rows × 9 features
- Target: `MedHouseVal` (Median House Value in $100,000s)

### Features

- `MedInc`: Median Income
- `HouseAge`: Median House Age
- `AveRooms`: Average Rooms per Household
- `AveBedrms`: Average Bedrooms per Household
- `Population`: Block Group Population
- `AveOccup`: Average Occupants per Household
- `Latitude`: Location Latitude
- `Longitude`: Location Longitude

## 🛠️ Workflow

1. **Data Loading & Exploration**
   - Summary stats and visualizations
2. **Preprocessing**
   - Scaling, train-test split
3. **Modeling**
   - Linear Regression (baseline)
   - Random Forest Regressor (improved accuracy)
4. **Evaluation**
   - MSE, R² Score
   - Predicted vs Actual plot

## 📊 Visualizations

- Correlation Heatmap
- Distribution Plots
- 3D Scatter Plots (via `plotly`)
- Predicted vs Actual Value Plots

## 🧪 Results

| Model               | MSE   | R² Score |
|--------------------|-------|----------|
| Linear Regression   | 0.53  | 0.61     |
| Random Forest       | 0.28  | 0.82     |

## 📁 Requirements

Install packages:


