# Global Space Exploration Data Analysis & Predictive Modeling

This project analyzes global space exploration missions from 2000 to 2024, uncovering insights about mission types, budgets, success rates, and technological adoption. Additionally, it features a predictive model using Random Forest Regression to estimate mission success rates based on mission characteristics.

## Dataset Overview

- **Source:** [Global Space Exploration Dataset](https://www.kaggle.com/datasets/atharvasoundankar/global-space-exploration-dataset-2000-2025/)
- **Records:** ~3,000 missions
- **Features:** Country, Year, Budget, Mission Type, Success Rate, Technology Used, Satellite Type, Duration, Collaborations

## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (RandomForestRegressor)
- Jupyter Notebook

## Exploratory Data Analysis (EDA) Highlights

- **Reusable rockets** and **AI navigation** technologies show increasing adoption over time.
- **Communication satellites** dominate deployment, highlighting global connectivity priorities.
- **Mission success rates** have steadily improved since 2000, reflecting advancements in technology and planning.
- **Correlation heatmap** shows weak linear relationships, suggesting complex mission factors beyond budget and duration.

## Machine Learning Model: Random Forest Regressor

| Metric                  | Score       |
|-------------------------|-------------|
| R² Score                | ~ -0.12     |
| Mean Absolute Error | ~13.91%     |
| Mean Squared Error | ~259.30     |

> *Insight:*  
> The model revealed limited predictive power, indicating that mission success likely depends on complex factors not fully captured in the dataset, such as technical challenges and mission objectives.

## Visualizations Included

- Total mission budget over time
- Success rate trends
- Satellite type distribution
- Technology adoption over years
- Correlation heatmap
- Feature importance from Random Forest model

## How to Install

1. Clone this repository
2. Install dependencies
3. Launch Jupyter Notebook
4. Explore the analysis and model

## Future Work

- Incorporate additional data sources (mission complexity, technical specs)
- Improve predictive model with feature engineering
- Build an interactive Tableau dashboard
- Explore classification models ( predicting mission type)
