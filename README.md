# 7th Semester Summer Internship – Data Analytics

# Week 1 Report

A concise summary of activities, learnings, and outputs achieved during the first week of my 7th semester summer internship in Data Analytics.

---

## 🚀 Internship Overview

This repository captures my Week 1 progress as I embark on a comprehensive data analytics learning path during my 7th semester summer internship. It covers:

- Foundational concepts and tool setup  
- Data cleaning and manipulation in Excel and Python  
- Exploratory data analysis (EDA)  
- Data visualization tool introduction  
- SQL query practice  
- Initial capstone project planning  

---

## 📅 Week 1 Breakdown

### 1. Onboarding & Analytics Foundations
- **Concepts Covered**  
  - Analytics lifecycle, data types (structured, unstructured, semi-structured)  
- **Environment Setup**  
  - Installed Anaconda (Jupyter), Microsoft Excel, Power BI Desktop (Tableau Public installed as an alternative)  
- **Courses & Tutorials**  
  - Completed IBM’s beginner analytics YouTube playlist  
- **Hands-On Task**  
  - Imported a sample CSV into Excel, calculated averages, created pivot tables & charts  

### 2. Data Cleaning & Manipulation in Excel & Python
- **Key Topics**  
  - Handling missing values, duplicates, inconsistent formats  
- **Excel Practice**  
  - Cleaned a “messy” dataset by removing duplicates and standardizing date formats  
- **Python & Pandas**  
  - Loaded the Titanic dataset; used `df.info()`, `df.describe()`; imputed missing ages; dropped irrelevant columns  

### 3. Exploratory Data Analysis (EDA)
- **Descriptive Statistics**  
  - Central tendency, dispersion, correlation  
- **Visualization Tools**  
  - Used `matplotlib`, `seaborn` for histograms, boxplots, heatmaps  
  - Generated an automated EDA report with `pandas_profiling`  
- **Notebook Deliverable**  
  - Jupyter Notebook documenting insights and annotated graphs  

### 4. Data Visualization Tools
- **Power BI Introduction**  
  - Data import, Query Editor, Report Canvas overview  
- **Dashboard Prototype**  
  - Regional sales slicers; KPIs for revenue & profit margin  
- **Next Steps**  
  - Replicate in Tableau Public with interactive map and filters  

### 5. SQL for Data Analytics
- **Core SQL Skills**  
  - SELECT, WHERE, JOIN, GROUP BY, ORDER BY, aggregate functions  
- **Practice Platforms**  
  - Mode Analytics, HackerRank  
- **Business Queries**  
  - Solved 10 real-world queries on a sample eCommerce dataset  
- **Integration**  
  - Connected Azure SQL to Power BI for live visualization  

### 6. Capstone Project Initiation
- **Dataset Selection**  
  - Titanic dataset from Kaggle  
- **Scope & Deliverables**  
  1. Data cleaning & preprocessing  
  2. EDA & insights  
  3. Interactive dashboard (Power BI/Tableau)  
  4. Final report & mentor presentation  

# Week 2 Report

---

## 🔍 Project Title: Customer Behavior & Revenue Optimization for E-Commerce Business

### 🎯 Objective
Analyze customer purchase patterns, churn behavior, product trends, and marketing performance to generate insights that improve retention, sales, and overall business performance.

### 📊 Dataset
- **Source**: Cleaned Dataset provided by Team A
- **Base**: E-Commerce Public Dataset (Olist)
- **File**: `master_dataset.csv`

---

## 🧩 Task 3 – Customer Segmentation

### 📌 Key Steps:
1. **RFM Analysis**: Recency, Frequency, Monetary values for each customer
2. **Clustering**: MiniBatchKMeans & HDBSCAN applied for segmentation
3. **Visualization**: PCA and t-SNE used to visualize clusters
4. **Strategy Recommendation**: Marketing actions based on customer segments

### 🧪 Implementation Highlights:
- **Data Preparation**: Cleaned data, parsed datetime, removed nulls
- **Feature Extraction**: RFM metrics calculated
- **Preprocessing**: StandardScaler applied, filtered invalid data
- **Clustering Algorithms**:
  - MiniBatchKMeans: Fast, scalable clustering
  - HDBSCAN: Detects noise & density-based clusters
- **Dimensionality Reduction**: PCA and t-SNE for visualization
- **Segment Strategy**:
  - VIP: Upselling, Rewards
  - At-Risk: Win-back Campaigns
  - Low-Value: Discounts
  - Mid-Value: Loyalty Programs

### 📈 Business Value:
- Personalized marketing
- Efficient resource allocation
- Churn prevention & portfolio analysis

### 🔗 Code Notebook: `Week_2_Task_1` (Google Colab)

---

## 🧠 Task 4 – Churn Prediction Model

### 📌 Key Steps:
1. **Label Customers**: Based on last purchase within 180 days
2. **Feature Engineering**: Tenure, complaints, frequency, satisfaction
3. **Model Training**: Logistic Regression, Random Forest, XGBoost, Neural Net
4. **Evaluation**: Accuracy, Precision, Recall, ROC-AUC, Confusion Matrix

### 🧪 Implementation Highlights:
- **Preprocessing**: Date parsing, imputation, scaling
- **Models**:
  - Logistic Regression (Baseline)
  - Random Forest
  - XGBoost
  - Neural Network (2 layers + Dropout)
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall
  - ROC Curve, AUC, Confusion Matrix

### 📈 Business Value:
- Early churn detection
- Targeted retention strategies
- Customer lifetime value optimization

### 🔗 Code Notebook: `Week_2_Task_2` (Google Colab)

---

## 📊 Task 6 – Business Dashboard Development

### ⚙ Tools: Power BI / Tableau

### 💡 Dashboard KPIs:
- Total Sales, Avg. Basket Size, Churn Rate, LTV
- Sales by Product, Region, Segment
- Filters: Time, Region, Product, Segment
- Geo-map of customer activity

### 📤 Deliverable: Exported dashboard (Web / PDF)

---

## 📈 Task 7 – Predictive Revenue Modeling

### 🎯 Objective:
Forecast future revenue using time-series and regression models.

### 📌 Forecasting Methods:
1. **Prophet**: 30-day prediction, seasonality handling
2. **ARIMA**: Auto-parameter tuning (p,d,q), non-seasonal model
3. **Regression**: Uses price & freight value for monthly forecasts

### 📊 Scenario Analysis:
- +10% marketing spend simulation
- Model performance: MAE, RMSE

### 📈 Business Value:
- Revenue target setting
- Scenario-based planning
- Demand forecasting & budget support

### 🔗 Code Notebook: `Week_2_Task_3` (Google Colab)

---

## 🔮 Future Enhancements
- Add behavioral features (session/product categories)
- Time-based segmentation & transition analysis
- A/B testing and campaign validation
- Ensemble models, deep learning (LSTM/Transformer)
- Lifetime value modeling & hierarchical forecasts
