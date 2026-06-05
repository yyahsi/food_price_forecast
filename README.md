# food_price_forecast
The goal of this ML project is to predict the prices of common breakfast food items across different cities using economic and geographic data. This matters because food prices affect cost of living, inflation, and consumer purchasing power, so accurate forecasts can help governments, businesses, and consumers make better decisions.

Dataset Source: https://www.kaggle.com/datasets/waddahali/global-grocery-inflation-20252026

This food prices dataset is fairly recent and no ML model is yet trained on it, only a statiscial review of the data exists.

p1/:  Exploratory data analysis was used to investigate distributions, trends, and relationships between variables. Correlation analysis, boxplots, category-level comparisons, and geographic visualizations were used to understand potential drivers of food prices.

p2/ Linear and polynomial regression and analysis:
Part 2 focused on forecasting short-term global food prices using regression models and historical monthly price data. Multiple Linear Regression, Polynomial Regression, Ridge, and Lasso models were tested using a leakage-aware city-based split. All models showed extremely high accuracy, but Lasso was the best performing one amongst them.
Updated:

p3/ extends the project with advanced regression models and model comparison. The analysis contrasts prediction performance with and without  price information, applies hyperparameter tuning, and uses PCA and clustering to investigate hidden patterns in the data.
