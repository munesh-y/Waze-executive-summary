# Waze-executive-summary
Data analysis project to identify and reduce user churn in Waze using EDA and statistical insights
# Waze Churn Analysis Project

This repository contains a data analytics project focused on understanding and reducing user churn on the Waze app.  
The project uses exploratory data analysis (EDA) and statistical insights to identify patterns in user behavior and help improve retention.

## 📂 Project Contents
- **Waze project lab.ipynb** – Jupyter Notebook with EDA, visualizations, and initial churn analysis.
- **Waze-executive-summary.pptx** – Executive summary presentation of key insights and recommendations.

## 📊 Key Insights
- Users who used the app **more frequently** were much less likely to churn.
- **Distance driven per day** had a *positive correlation* with churn — long-distance drivers churned more.
- **Number of driving days** had a *negative correlation* with churn — more active users were retained better.
- Some variables contained **outliers or inconsistent values** (e.g., `driven_km_drives`, `activity_days`, `driving_days`), requiring further data cleaning.

## 🔍 Next Steps
- Investigate discrepancies between `number_of_sessions`, `driving_days`, and `activity_days`.
- Explore user profiles to understand why long-distance drivers churn more.
- Run deeper statistical modeling to predict churn and test interventions.

## 🛠️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/waze-churn-analysis.git
   cd waze-churn-analysis
