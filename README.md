# 🚴‍♀️ **Bike Sharing Demand Prediction**

> A data-driven project to predict bike-sharing demand using **Multiple Linear Regression**.

---

## 📚 **Table of Contents**
- [General Information](#general-information)
- [Business Problem](#business-problem)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Model Evaluation](#model-evaluation)
- [Insights and Recommendations](#insights-and-recommendations)
- [How to Run the Project](#how-to-run-the-project)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

---

## 📊 **General Information**
BoomBikes, a US-based bike-sharing service provider, aims to predict bike demand to optimize their business strategy post-pandemic. The objective of this project is to identify the key factors affecting bike demand and build a predictive model to estimate the daily demand for shared bikes.

---

## 📝 **Business Problem**
BoomBikes faced revenue challenges due to the COVID-19 pandemic. To recover efficiently, they want to:
- Identify significant variables impacting bike demand.
- Build a reliable predictive model.
- Optimize inventory and operational strategies based on predictions.

---

## 📊 **Dataset Description**
The dataset contains daily records of bike demand with various factors:
- **Date-related Features:** Year, Month, Weekday.
- **Weather-related Features:** Temperature, Humidity, Windspeed.
- **Categorical Features:** Season, Weather Situation.
- **Target Variable:** Total bike rentals (`cnt`).

---

## ⚙️ **Methodology**
1. **Data Preprocessing:**
   - Cleaned and standardized data.
   - Handled categorical variables using one-hot encoding.
2. **Exploratory Data Analysis (EDA):**
   - Analyzed patterns and trends.
   - Correlation analysis.
3. **Model Building:**
   - Feature selection using RFE.
   - Built a Multiple Linear Regression model.
4. **Model Evaluation:**
   - Evaluated using R², RMSE, and Residual Analysis.
5. **Insights and Recommendations:**
   - Derived actionable insights.

---

## 🛠️ **Technologies Used**
- **Python 3.9**
- **Pandas 1.3.3**
- **NumPy 1.21.2**
- **Matplotlib 3.4.3**
- **Seaborn 0.11.2**
- **Scikit-learn 0.24.2**
- **Jupyter Notebook**

---

## 📊 **Model Evaluation**
- **R² Score (Train):** 0.85
- **R² Score (Test):** 0.83
- **RMSE (Test):** 50.3
- **MAE (Test):** 32.5

Residual plots and visual analysis confirm that the model assumptions are valid.

---

## 💡 **Insights and Recommendations**
1. Temperature and season significantly impact bike demand.
2. Weather situations like clear skies boost bike rentals.
3. Year (`yr`) shows an increasing trend in bike usage.
4. High humidity and heavy rain reduce demand.

---

## ▶️ **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook and execute all cells.
4. Review the model outputs and analysis.

---

## 🏁 **Conclusion**
The Multiple Linear Regression model successfully predicts bike demand and identifies key drivers affecting demand patterns. This insight can help BoomBikes optimize their resources and enhance customer satisfaction.

---

## 🙌 **Acknowledgements**
- Dataset Source: [Fanaee-T, Hadi, and Gama, Joao](http://dx.doi.org/10.1007/s13748-013-0040-3)
- Inspired by data science capstone projects.

---

## 📬 **Contact**
Created by **[@ganlak]** – feel free to reach out for queries or collaborations.

---

**🚀 Let's Ride Towards Data-Driven Success!**