# Air Quality & Health Impact Analysis

## 📌 Project Overview
Air pollution is one of the leading environmental risks to global health. This project focuses on analyzing atmospheric pollutants and their direct correlation with health outcomes. By leveraging data-driven insights, the project aims to identify high-risk zones and predict potential health impacts based on pollutant concentrations (PM2.5, PM10, NO2, etc.).

## 📊 Dataset Description
The analysis utilizes a comprehensive air quality dataset containing:
* **Pollutant Levels:** Measurements of PM2.5, PM10, Nitrogen Dioxide (NO2), Sulfur Dioxide (SO2), and Carbon Monoxide (CO).
* **Geographical Data:** Location-based tracking of air quality.
* **Health Indicators:** Respiratory and cardiovascular health impact scores.

## 🛠️ Data Pipeline & Preprocessing
To ensure model accuracy, the following data science techniques were applied:
1. **Handling Missing Values:** Applied mean/median imputation for sensor-related data gaps.
2. **Feature Engineering:** Created an **Air Quality Index (AQI)** categorization to simplify complex pollutant data into actionable health risk levels (Good, Moderate, Unhealthy, Hazardous).
3. **Data Normalization:** Scaled numeric features to improve the performance of distance-based machine learning algorithms.
4. **Outlier Detection:** Identified and addressed sensor anomalies to prevent skewed results.



## 🚀 Key Analysis & Modeling
The project explores the relationship between environment and health through:
* **Correlation Heatmaps:** Visualized how specific pollutants (like PM2.5) have a higher statistical impact on health scores compared to others.
* **Trend Analysis:** Observed seasonal variations in air quality to predict "high-risk" months.
* **Predictive Modeling:** Built a classification/regression model to predict the **Health Impact Class** based on current pollutant levels.

## 📈 Key Insights
* **Primary Driver:** PM2.5 was identified as the strongest predictor of respiratory-related health issues.
* **Threshold Analysis:** Determined the pollutant concentration levels at which health risks transition from "Moderate" to "High."



## 🛠️ Tech Stack
* **Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (Random Forest / Logistic Regression)
* **Visualization:** Seaborn, Matplotlib, Plotly (for interactive maps)

## 🚀 How to Use
1. Clone the repository: `git clone https://github.com/RijaBhomi/Air-Quality-and-Health-Impact.git`
2. Install requirements: `pip install -r requirements.txt`
3. Run the analysis: `jupyter notebook Air_Quality_Analysis.ipynb`
