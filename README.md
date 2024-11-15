# Machine Learning for User Classification

## Project Overview

This project aims to predict whether students will upgrade from a free plan to a paid plan based on their engagement with the 365 Data Science platform. The dataset consists of user engagement metrics, such as the number of days spent on the platform, minutes of content watched, and the number of courses started. The objective is to apply machine learning classification models to make predictions.

### Business Objective:
By identifying students likely to upgrade, this model can help 365 Data Science (and similar online platforms) target advertisements, send exclusive offers, and optimize their marketing strategies, ultimately driving revenue growth.

## Dataset

The dataset used in this project is `ml_datasource.csv`, which contains the following features:

- `days_on_platform`: Number of days the user has spent on the platform.
- `minutes_watched`: Total minutes of content watched by the user.
- `courses_started`: Number of courses the user has started.
- `upgrade`: Target variable indicating whether the student upgraded to a paid plan (1 for upgrade, 0 for no upgrade).

## Project Structure

This repository contains the following files:

- **ml_datasource.csv**: The dataset for the project.
- **Machine Learning Project.ipynb**: The Jupyter notebook containing the project code and tasks for each part of the project.

### Project Requirements:
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **statsmodels**: For statistical modeling.
- **scikit-learn**: For machine learning models.
- **numpy**: For numerical operations.
- **seaborn**: For data visualization.

You can install the required libraries using:

```bash
pip install pandas matplotlib statsmodels scikit-learn numpy seaborn
