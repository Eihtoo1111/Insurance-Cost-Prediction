# Insurance-Cost-Prediction
Predicting annual medical costs from patient demographics, lifestyle habits, and chronic conditions using linear, ridge, and polynomial regression on a 5,000-patient synthetic healthcare dataset.

This project looks at how personal risk factors relate to a patient’s yearly healthcare spending. Using a synthetic but realistically correlated dataset of 5,000 patients, we explore how age, BMI, smoking, physical activity, sleep, stress, and chronic conditions (diabetes, hypertension, heart disease, asthma) affect annual medical cost in USD.

We then compare three supervised regression models (linear, ridge, and polynomial) to see which one predicts cost most accurately. Each model is tested with two random states (0 and 42) to check that results stay consistent across different train/test splits.

Healthcare utilization and prior-year cost were left out on purpose to avoid data leakage, so the models estimate cost using only information known before care happens.
