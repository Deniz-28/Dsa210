# Social Media and Mental Health Analysis

## Motivation
Mental health and social media usage have become increasingly connected in modern daily life. This project aims to investigate whether social media behavior can be associated with stress levels and mental health indicators using data science techniques.

## Dataset
The dataset includes information about:
- age
- gender
- occupation
- social media platform preferences
- daily social media usage
- sleep habits
- stress level
- emotional reactions to social media
- FOMO behavior
(The dataset contains both numerical and categorical variables.)

## Exploratory Data Analysis (EDA)

EDA techniques were used to better understand the relationships between variables.
The analysis explored:
- stress level distributions,
- social media usage trends,
- relationships between sleep and stress,
- platform preferences by age groups,
- and behavioral patterns related to social media usage.
Several visualizations such as histograms, bar charts, and correlation analyses were used.

## Hypothesis Testing

Hypothesis testing was performed to analyze whether social media related behaviors have statistically significant relationships with stress levels.The results suggested that certain behavioral factors such as excessive usage and emotional sensitivity to posts may be associated with higher stress levels.

## Machine Learning

For the machine learning stage, regression models were used to predict daily stress levels of participants based on their social media usage patterns, demographic features, sleep habits, and social media behavior.
### Target Variable
- Daily stress level

### Models Used
- Linear Regression
- Random Forest Regressor

### Evaluation Metrics
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


