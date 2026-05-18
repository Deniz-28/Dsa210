# Social Media and Mental Health Analysis

## Project Description
This project analyzes the relationship between social media usage and mental health.

## Dataset
The dataset includes:
- Age
- Gender
- Daily social media usage
- Stress level
  
## Machine Learning

For Milestone 2, I applied machine learning models to predict the daily stress level of participants based on their social media usage patterns, demographic features, sleep habits, and social media behavior.

The target variable is daily stress level.

The models used are:
- Linear Regression
- Random Forest Regressor

The models were evaluated using:
- MAE
- RMSE
- R² Score

## Why are the R² scores low?

The regression models produced relatively low R² scores, indicating limited predictive capability. This is expected because mental health is affected by many different factors beyond social media usage alone.

Possible reasons include:

- limited number of features in the dataset,
- self-reported survey noise,
- complex human behavior,
- weak linear relationships between variables,
- insufficient dataset size.

Therefore, social media usage alone is not enough to strongly predict mental health outcomes.

## Model Interpretation

Feature importance analysis suggests that some variables contributed more strongly to prediction performance than others.

Variables related to daily social media usage and sleep patterns showed stronger influence compared to other features. However, no single variable was sufficient to explain mental health outcomes on its own.

This suggests that mental health is a multidimensional problem affected by many interacting factors.

## Conclusion

This project investigated the relationship between social media usage and mental health through exploratory data analysis, hypothesis testing, and machine learning methods.

Although the machine learning models achieved relatively low R² scores, the analysis still revealed meaningful patterns between social media behavior and mental health indicators.

The findings suggest that mental health cannot be explained only through social media usage, since many additional psychological, environmental, and lifestyle factors also play important roles.
