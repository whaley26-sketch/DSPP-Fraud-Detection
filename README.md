# Fraud Detection Analysis 🔍

## Project Overview 📝

This project was completed as part of the DSPP Data Science apprenticeship programme. The aim was to develop a machine learning model capable of identifying fraudulent transactions whilst balancing fraud detection performance against operational review costs.

---

## Methodology 🏗️

The project followed a Medallion Architecture approach:

- Bronze Layer: Raw data ingestion
- Silver Layer: Data cleaning and feature engineering
- Gold Layer: Model development and evaluation

- ⚠️ Due to GitHub file size limits, raw data files are stored locally. All transformation/cleaning logic is reproducible via the notebooks provided.

---

## Models Evaluated 🤖 

### Logistic Regression 🧠

Used as a baseline model to establish performance benchmarks.

### XGBoost 🚀

Used as the final model due to superior predictive performance.

---

## Key Visualisations 📈

- Correlation Heatmap
- Confusion Matrix
- Feature Importance
- Model Comparison

---

## Business Impact 📊

- Fraudulent transactions can result in financial losses, customer dissatisfaction, reputational damage, and operational costs associated with manual investigations
- This project developed a machine learning solution capable of identifying potentially fraudulent transactions before they are processed. An XGBoost model was selected due to its superior performance when compared to a Logistic Regression baseline model.
- The model achieved a high fraud detection rate (recall), ensuring that the majority of fraudulent transactions were identified for review. In a fraud detection context, missing fraudulent activity (false negatives) can be more costly than reviewing additional genuine transactions.
- The project demonstrates how machine learning can support risk management processes by:

- Reducing financial losses from fraudulent transactions.
- Prioritising high-risk transactions for investigation.
- Improving operational efficiency through automated risk scoring.
- Supporting data-driven decision making.
- Providing an auditable and reproducible modelling pipeline using Medallion Architecture.

- Although developed using a public Kaggle dataset, the approach could be adapted within financial services environments to enhance existing fraud monitoring controls.

## Repository Structure 📂

- notebooks/
- screenshots/
- README.md
- requirements.txt
- .gitignore
- LICENSE

---

## Notes 📌

- Built as a first year on a level 6 Data Science Apprenticeship
- Raw data sourced from Kaggle.com
- Project is licensed under the MIT License
