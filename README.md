Delivery Duration Prediction (DoorDash Case Study)

Project Overview

This project replicates a real-world data science take-home assignment from DoorDash.
The task is to predict delivery duration (in seconds) for each order, based on historical order, store, and market features.

The project covers the complete end-to-end machine learning workflow: data cleaning, EDA with storytelling, feature engineering, modeling, evaluation, and insights for business impact.

Dataset

Source: DoorDash dataset (historical_data.csv)

Size: ~197,000 rows × 16 features

Target: delivery_duration_sec → time from order creation to delivery

Project Workflow

Data Understanding → Dataset structure, target analysis

Data Cleaning & Preprocessing → Missing values, outliers, datetime conversion

EDA with Storytelling → Professional plots (histogram, pie, bar, line, heatmap)

Feature Engineering → Derived features: rush hour, weekend, order size

Modeling

Baseline: Linear Regression, Decision Tree

Advanced: Random Forest, XGBoost, LightGBM

Model Evaluation

Metrics: MAE, RMSE, R²

Visual comparisons (side-by-side & 3-panel subplot)

Interpretability → Feature importance (XGBoost) & error analysis scatterplot

Results

Best Model: XGBoost

Performance:

MAE ≈ 602 sec (~10 minutes)

RMSE ≈ 778 sec

R² = 0.36

Key Insights:

Market dynamics (on-shift & busy dashers, outstanding orders) strongly affect delivery duration

Larger & more expensive orders generally take longer

Delivery time varies significantly by hour of day and day of week

Cuisine type (store category) also influences preparation & delivery speed

Project Structure

data/ → raw & cleaned datasets

plots/ → saved plots (EDA, model comparison, feature importance, error analysis)

notebooks/ → Jupyter/Colab notebooks

results/ → final results table & metrics

README.md → project documentation

Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM

Future Improvements

Hyperparameter tuning for XGBoost/LightGBM

Adding advanced time-series features

Exploring deep learning approaches (MLP / Neural Networks)

📬 Contact - Md. Rabbi Hasan | Data Scientist 📧arafatrabbi668@gmail.com | LinkedIn https://www.linkedin.com/in/md-rabbi-hasan-3249652b1 Passionate about turning raw data into real-world insights through clear, compelling storytelling.
