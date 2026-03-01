# COVID-19 Data Analysis Project

This project focuses on analyzing COVID-19 data, with a particular emphasis on Denmark, Europe, and global comparisons. The dataset includes time series information on:

- Confirmed cases
- Deaths
- Recoveries
- Tests
- Vaccinations
- Hospitalizations
- Policy measures implemented to control the pandemic

## Key Components of the Project

### 1. Data Exploration (EDA)
- Examined missing values, reporting frequency, and data reliability.
- Compared epidemiological variables (cases, deaths, tests, vaccinations) across countries.
- Highlighted that Denmark had high-quality, daily-reported data with extensive testing and vaccination coverage.

### 2. Policy Measures Analysis
- Compared government interventions using indices such as:
  - Containment and Health Index
  - Economic Support Index
- Observed that Denmark implemented stricter testing policies relative to regional averages.

### 3. Regression Modeling
- Applied linear and multiple regression models to predict confirmed cases and deaths.
- Evaluated model performance using metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R²
- Tested assumptions of linear regression:
  - Residual distributions
  - Homoscedasticity
  - Normality
- Explored multicollinearity and assessed the impact of variables like hospitalizations and ICU admissions.

### 4. Comparing Algorithms
- Tested various predictive algorithms including:
  - Linear Regression
  - Support Vector Regression (SVR)
  - Regression Trees
  - Random Forest
- Found Random Forest to perform best, producing accurate predictions and well-distributed residuals.

## Conclusions
- Regression-based models can reasonably predict cases and deaths given well-prepared data.
- Global analysis is possible but limited by missing data, reporting inconsistencies, and potential manipulation.
- Localized analysis, particularly for countries with reliable data like Denmark, provides more accurate insights.
