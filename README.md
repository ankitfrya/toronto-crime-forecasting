# Toronto Crime Forecasting

## Project Overview

The **Toronto Crime Forecasting Project** is a machine learning and time-series forecasting project that analyses historical crime patterns across Toronto.

The objective is to investigate whether historical crime data can be used to forecast monthly crime counts across different Toronto neighbourhoods and crime categories.

The project explores statistical forecasting techniques and machine learning algorithms, with an emphasis on reliable model evaluation and responsible use of public safety data.

## Objectives

- Analyse historical crime patterns across Toronto.
- Identify trends and seasonal variations.
- Develop monthly crime forecasting models.
- Compare statistical forecasting methods with machine learning algorithms.
- Evaluate models using chronological validation.
- Investigate forecasting errors and model limitations.
- Explore responsible and ethical applications of crime data.

## Data Source

**Toronto Open Data – Major Crime Indicators / Community Safety Indicators**

Official dataset:
https://open.toronto.ca/dataset/major-crime-indicators/

The dataset includes information such as:

- Occurrence date and time.
- Crime category.
- Offence type.
- Toronto neighbourhood.
- Geographic coordinates.

The five crime categories currently being investigated are:

1. Assault
2. Auto Theft
3. Break and Enter
4. Robbery
5. Theft Over

Raw datasets are not included in this repository. Refer to the official Toronto Open Data source for access.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- Statsmodels
- JupyterLab
- Git and GitHub

## Methodology

The project follows these stages:

1. Data acquisition and exploration.
2. Data cleaning and preparation.
3. Exploratory data analysis.
4. Feature engineering.
5. Baseline forecasting.
6. Statistical time-series modelling.
7. Machine learning model development.
8. Chronological model validation.
9. Error analysis and model comparison.
10. Documentation and responsible AI considerations.

## Forecasting Approaches

Methods explored or planned include:

**Baseline methods**
- Naive forecasting.
- Seasonal naive forecasting.
- Moving averages.

**Statistical forecasting**
- Simple Exponential Smoothing.
- Holt's Linear Trend Method.
- Holt-Winters.
- ARIMA and SARIMA.

**Machine learning**
- Linear Regression.
- Random Forest.
- Gradient Boosting / LightGBM.

## Current Progress

Completed:
- Python development environment setup.
- Initial ML foundations and model experiments.
- Toronto crime dataset acquisition and exploration.
- Neighbourhood-level monthly crime aggregation.
- Crime-category-level monthly aggregation.
- Historical feature engineering.
- Chronological training and testing splits.
- Initial Random Forest experiments.
- Baseline forecasting comparisons.
- Simple Exponential Smoothing experiment.

Currently working on:
- Classical time-series forecasting.
- Understanding trend and seasonality.
- Improving forecasting methodology.
- Comparing statistical and machine learning approaches.

## Evaluation Metrics

The project uses:

- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).

Chronological validation is used to respect the temporal ordering of observations and reduce future-data leakage.

## Data Limitations and Ethical Considerations

This project uses police-recorded crime indicators. Recorded incidents do not represent all crime or the true underlying level of criminal activity.

Potential limitations include:
- Under-reporting of incidents.
- Changes in reporting practices.
- Missing or incomplete geographic information.
- Changes in crime patterns over time.
- Potential bias in recorded crime data.

The intended application is aggregate area-level forecasting and research. Predictions should not be used to label individuals, justify discriminatory policing, or make decisions about individuals.

## Repository Structure

```text
toronto-crime-forecasting/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Evaluate additional statistical forecasting models.
- Develop neighbourhood × crime category forecasting.
- Explore additional public datasets.
- Investigate geospatial patterns.
- Improve model explainability and evaluation.
- Develop a forecasting dashboard as a future extension.

## Author

An independent machine learning and data science learning project.
