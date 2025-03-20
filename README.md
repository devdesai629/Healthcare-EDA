#Medical Appointments Data - Exploratory Data Analysis (EDA)

Overview

This project performs an exploratory data analysis (EDA) on a dataset containing medical appointment records. The goal is to clean the data, explore trends, and identify factors influencing patient no-shows.

Dataset

The dataset consists of medical appointment records with various attributes, including:

Patient ID: Unique identifier for each patient.

Scheduled Day: Date when the appointment was scheduled.

Appointment Day: Date of the actual appointment.

No-show: Indicates whether the patient attended the appointment.

Other Features: Demographic and medical history details.

Key Steps in Analysis

1. Data Cleaning

Verified that the dataset has no missing values.

Created a copy of the dataset for safe manipulation.

Extracted weekday information from schedule and appointment dates.

2. Data Exploration

Converted categorical variables into dummy variables.

Analyzed the correlation of all predictors with the 'No-show' variable.

Performed bivariate analysis to assess relationships between features.

3. Visualizations & Insights

Distribution plots and histograms were generated to explore patterns.

Correlation matrices were used to identify relationships between variables.

Analyzed factors affecting appointment attendance trends.

Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

How to Run the Notebook

Install required libraries:

Open the Jupyter Notebook and execute all cells sequentially.

Results & Insights

No missing values in the dataset.

Strong correlations observed between appointment attendance and certain features.

Specific weekdays exhibited higher no-show rates.

Further analysis could help develop predictive models.

Next Steps

Implement machine learning models to predict patient no-shows.

Conduct deeper feature engineering for better insights.

Optimize visualization techniques for clearer trends.

Author

Dev Desai
