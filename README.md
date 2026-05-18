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

Feature importance analysis was performed using the Random Forest Regressor model.

The most influential features included:
- daily social media usage time,
- frequency of arguments caused by social media,
- emotional reactions to social media posts,
- fear of missing out (FOMO),
- comparison with others on social media.

These findings suggest that emotional and behavioral aspects of social media usage may have a stronger relationship with stress levels than demographic factors alone. However, no single feature was sufficient to strongly predict mental health outcomes on its own, which supports the relatively low R² scores obtained by the models.

## Conclusion

This project investigated the relationship between social media usage and mental health through exploratory data analysis, hypothesis testing, and machine learning methods.

Although the machine learning models achieved relatively low R² scores, the analysis still revealed meaningful patterns between social media behavior and mental health indicators.

The findings suggest that mental health cannot be explained only through social media usage, since many additional psychological, environmental, and lifestyle factors also play important roles.
