# Rain Prediction in Australia

Welcome to the **Rain Prediction in Australia** project repository! This project involves applying various machine learning algorithms to predict whether there will be rain in Australia on the following day. The dataset used in this project is sourced from the Australian Government's Bureau of Meteorology. The objective is to build a classifier that can effectively predict rain based on meteorological features.

## Project Overview

In this project, we will leverage the machine learning skills we've acquired over a five-week period to develop a Jupyter notebook where we implement and evaluate different classification algorithms for predicting rain.

## Dataset

The dataset is obtained from the Australian Government's Bureau of Meteorology and contains essential weather condition information. The task is to predict whether there will be rain the next day based on the provided features.

You can download the dataset from the [Australian Government's Bureau of Meteorology](#) or use an alternative source.

## Algorithms Used

We will explore several machine learning algorithms to build and assess our rain prediction models. The following algorithms will be employed:

1. Linear Regression
2. K-Nearest Neighbors (KNN)
3. Decision Trees
4. Logistic Regression
5. Support Vector Machines (SVM)

## Evaluation Metrics

We will evaluate our models using the following metrics:

- **Accuracy Score**: Ratio of correctly predicted instances to the total number of instances.
- **Jaccard Index**: Measures the similarity between predicted and actual classes.
- **F1-Score**: Harmonic mean of precision and recall.
- **LogLoss**: Quantifies the accuracy of predicted probabilities.
- **Mean Absolute Error**: Measures average absolute differences between predicted and actual values.
- **Mean Squared Error**: Measures average squared differences between predicted and actual values.
- **R2-Score**: Evaluates the predictability of the dependent variable from independent variables.

## Project Structure

The repository structure is as follows:

- `Weather.csv`: The dataset sourced from the Australian Government's Bureau of Meteorology.
- `notebooks/`: Directory housing the Jupyter notebook (`Machine Learning Project.ipynb`) where data preprocessing, algorithm implementation, and model evaluation take place.
- `README.md`: The document you are currently reading, providing a project overview, dataset details, employed algorithms, and evaluation metrics.

## The Dataset - Weather.csv

The primary dataset for this project is `Weather.csv`, sourced from the Australian Government's Bureau of Meteorology. It contains a comprehensive set of meteorological features and historical weather data. Each row in the dataset represents weather conditions for a specific day.

**Features:**
- Date: Date of the recorded weather data
- Location: Geographic location of the weather station
- MinTemp: Minimum temperature for the day (in degrees Celsius)
- MaxTemp: Maximum temperature for the day (in degrees Celsius)
- Rainfall: Amount of rainfall recorded for the day (in millimeters)
- Evaporation: Daily evaporation (in millimeters)
- Sunshine: Number of hours of sunshine
- WindGustDir: Direction of the strongest wind gust
- WindGustSpeed: Speed of the strongest wind gust (in kilometers per hour)
- WindDir9am: Wind direction at 9 am
- WindDir3pm: Wind direction at 3 pm
- WindSpeed9am: Wind speed at 9 am (in kilometers per hour)
- WindSpeed3pm: Wind speed at 3 pm (in kilometers per hour)
- Humidity9am: Relative humidity at 9 am
- Humidity3pm: Relative humidity at 3 pm
- Pressure9am: Atmospheric pressure at 9 am (in hPa)
- Pressure3pm: Atmospheric pressure at 3 pm (in hPa)
- Cloud9am: Fraction of sky covered by clouds at 9 am
- Cloud3pm: Fraction of sky covered by clouds at 3 pm
- Temp9am: Temperature at 9 am (in degrees Celsius)
- Temp3pm: Temperature at 3 pm (in degrees Celsius)
- RainToday: Binary indicator of whether it rained today (Yes/No)
- RainTomorrow: Binary target variable indicating whether it will rain tomorrow (Yes/No)

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the `notebooks/` directory.
3. Open the Jupyter notebook (`rain_prediction.ipynb`) to start exploring the project.

Feel free to customize the code, experiment, and make enhancements as needed. Have a great time predicting rain! 🌧️
