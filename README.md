# NUS SDS Datahon 2024: Singlife

## Project Overview
This project focuses on addressing Singlife's challenge of potential policyholders hesitating and disengaging during the insurance acquisition process. We aim to leverage Singlife's dataset to identify critical touchpoints that contribute to customer drop-off. The goal is to derive actionable insights to streamline the application process, personalize communication, and enhance the overall customer experience. Ultimately, we seek to predict customer satisfaction and conversion rates, aiming to improve Singlife's market position.

## Methodology
* Data Analysis
This step inclides data expliration, data cleaning, and data engineering. We used pandas profiling to help us with understanding the raw data better before moving on to the next steps. This Exploratory Data Analysis (EDA) is done using ydata_profiling python package. the The data cleaning and feature engineering are done according to our findings from the EDA, and the code is included in the Notebook.

* Modelling
After several trial and error, we decided to use 3 models: XGBoost, Decision Tree, Logistic Regression, and an ensamble of the 3 of them. 


## Repository Contents

### 1. `NUS_DATATHON_SINGLIFE_286.ipynb`
A comprehensive Jupyter notebook detailing our analysis, following the given template. It includes our training model, data exploration, feature engineering, and model evaluation.

### 2.1 `singlife_datathon_minimal.html`
An HTML file featuring initial aggregations and visualizations of the raw Singlife data. Generated using `pandas_profiling`, this file serves as a crucial part of our EDA.

### 2.2 `singlife_datathon_cleaned_minimal.html`
An HTML file showcasing aggregations and visualizations of the Singlife data post-cleanup. Similar to 2.1, it's generated using `pandas_profiling` and is a vital component of our EDA, highlighting the effects of our data cleaning process.

## Packages
* pandas
* ydata_profiling https://github.com/ydataai/ydata-profiling

## Contributors
* Eric Neo
* Jaden Chang
* Hans Neddyanto Tandjung
* Hastuti Hera Hardiyanti
* Veronica Angelin Setiyo
