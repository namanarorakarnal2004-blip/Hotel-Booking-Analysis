# 🏨 Hotel Booking Analysis
### Travel & Hospitality — Customer Retention & Dynamic Pricing Analysis
> Infotact Solutions & Co. | Internship Project 2 | 2026

---

## 📌 Problem Statement
Hotels face significant revenue loss due to unoptimized pricing and 
unpredictable cancellations. This project analyzes historical booking 
data to uncover cancellation drivers and seasonal demand patterns.

---

## 🎯 Objectives
- Identify key factors driving customer cancellations
- Analyze seasonal booking and pricing trends
- Build foundation for a dynamic pricing engine

---

## 📊 Dataset
| Property | Details |
|----------|---------|
| Source | Kaggle — Hotel Booking Demand |
| Records | 119,390 rows |
| Features | 32 columns |
| Period | 2015 - 2017 |

---

## 🗓️ Project Roadmap

### ✅ Week 1 — Data Cleaning & Feature Engineering
- Handled missing values (agent, company, children, country)
- Treated outliers in ADR column
- Engineered features: total_nights, total_guests

### ✅ Week 2 — EDA & Statistical Analysis
- *Cancellation Rate: 37.04%*
- Correlation heatmap across 32 variables
- Monthly cancellation trend analysis
- Lead time vs cancellation behavior
  

## 🛠️ Tech Stack


![Python](https://img.shields.io/badge/Python-3.x-blue)




![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)




![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)

### ✅ Week 3 — Predictive Modeling (Churn Prediction)
- Logistic Regression model built using Scikit-Learn
- Model Accuracy: 69.42%
- ROC-AUC Score: 0.73
- Train-Test Split: 80/20
- Features used: lead_time, total_nights, total_guests, previous_cancellations, booking_changes, ADR, days_in_waiting_list
- Built a Logistic Regression model using Scikit-Learn.
- Predicted hotel booking cancellations using historical booking data.
- Achieved 69.42% Model Accuracy.
- Obtained ROC-AUC Score: 0.73.
- Performed 80:20 Train-Test Split.
- Selected key features:
- Lead Time
- ADR
- Total Nights
- Total Guests
- Previous Cancellations
- Booking Changes
- Days in Waiting List
- Evaluated model performance using confusion matrix and classification metrics.

  Week 4 — Power BI Dashboard & Business Intelligence
- Designed an interactive Hotel Booking Analysis Dashboard using Power BI.
- Created KPI Cards for:
       - Total Bookings
       - Cancelled Bookings
       - Non-Cancelled Bookings
       - Cancellation Rate
- Built interactive visualizations:
       - Monthly Cancelled Bookings Trend (Line Chart)
       - Cancelled Bookings by Hotel Type (Bar Chart)
       - Bookings by Customer Type (Donut Chart)
       - Cancelled Bookings by Market Segment (Column Chart)
- Added interactive Slicers for Hotel Type, Market Segment, and Arrival Day.
- Applied professional dashboard formatting with aligned visuals, borders, consistent color theme, and responsive layout.
- Generated business insights to support hotel booking and cancellation analysis.

## 📊 Project Outcomes

- Identified booking cancellation patterns.
- Built an interactive Power BI dashboard for business insights.
- Developed a machine learning model to predict booking cancellations.
- Improved data-driven decision making through visualization and predictive analytics.

## 🛠️ Skills Gained

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Machine Learning
- Data Visualization

  ## ⭐ Project Status

✅ Completed

## 👤 Author
*Naman Arora*
MBA — Business Analytics | Infotact Solutions Intern
