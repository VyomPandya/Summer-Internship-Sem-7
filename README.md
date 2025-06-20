# 7th Semester Summer Internship – Data Analytics

## Week 1 Report

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

---

## Week 2 Report

### 🔍 Project Title: Customer Behavior & Revenue Optimization for E-Commerce Business

#### 🎯 Objective
Analyze customer purchase patterns, churn behavior, product trends, and marketing performance to generate insights that improve retention, sales, and overall business performance.

#### 📊 Dataset
- **Source**: Cleaned Dataset provided by Team A  
- **Base**: E-Commerce Public Dataset (Olist)  
- **File**: `master_dataset.csv`

---

### 🧩 Task 3 – Customer Segmentation

#### 📌 Key Steps:
1. **RFM Analysis**: Recency, Frequency, Monetary values for each customer  
2. **Clustering**: MiniBatchKMeans & HDBSCAN applied for segmentation  
3. **Visualization**: PCA and t-SNE used to visualize clusters  
4. **Strategy Recommendation**: Marketing actions based on customer segments  

#### 🧪 Implementation Highlights:
- Cleaned and transformed data  
- Extracted RFM metrics  
- Applied clustering algorithms  
- Used PCA and t-SNE for dimensionality reduction  

---

### 🧠 Task 4 – Churn Prediction Model

#### 📌 Key Steps:
1. **Labeling**: Identified churned customers (180 days)  
2. **Feature Engineering**: Tenure, complaints, satisfaction  
3. **Models**: Logistic Regression, Random Forest, XGBoost, Neural Network  
4. **Evaluation**: Accuracy, Precision, ROC-AUC  

---

### 📊 Task 6 – Dashboard Development

#### ⚙ Tools:
- Power BI / Tableau  

#### 💡 KPIs:
- Churn Rate, Sales Volume, Customer Segments, Regional Performance  

---

### 📈 Task 7 – Predictive Revenue Modeling

#### 📌 Models Used:
- Prophet, ARIMA, Linear Regression  

#### 💡 Outcome:
- Forecasts and actionable insights to support financial decisions  

---

## Week 3 Report

### 📊 Project Title: Marketing Campaign Analytics & A/B Testing

#### 🧠 Key Objectives
- Explore marketing performance through data analysis  
- Simulate A/B testing scenarios and recommend strategies  
- Apply statistical tests and dimensionality reduction  

#### 🛠️ Tools Used
- Python (Pandas, Seaborn, Matplotlib)  
- Scikit-learn  
- SciPy  

---

### 📌 Summary of Tasks:
1. **Marketing Data Analysis**  
   - Performed EDA using Seaborn and Matplotlib  
   - Feature engineering (Age, TotalSpend)  

2. **A/B Testing Simulation**  
   - Implemented and interpreted t-tests  
   - Visualized response behaviors by group  

3. **Statistical Testing**  
   - Applied PCA for dimensionality reduction  
   - Conducted Chi-Square and ANOVA tests  

4. **Insight Generation**  
   - Created personas based on age, education, spend  
   - Generated recommendations for targeted campaigns  

---

### 🔭 Plans for Week 4:
- Build a Customer Lifetime Value (CLTV) model  
- Develop dashboards integrating churn and campaign analytics  
- Prototype a recommender system based on segmentation  

---

### 📚 References:
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [SciPy Documentation](https://docs.scipy.org/doc/scipy/)  
- [scikit-learn Clustering](https://scikit-learn.org/stable/modules/clustering.html)  

---

## Week 4 Report

### 📊 Project Title: Customer Lifetime Value & Dashboard Insights

#### 🧠 Key Objectives
- Evaluate campaign performance through A/B testing  
- Visualize customer behavior and value trends  
- Estimate and represent Customer Lifetime Value  

#### 🛠️ Tools Used
- Python (Plotly)  
- Power BI  
- scikit-learn  

---

### 📌 Summary of Tasks:
1. **Marketing Performance Analysis**  
   - Conducted A/B testing and statistical evaluations  
   - Compared campaign outcomes through visual comparisons  

2. **Interactive Visualizations**  
   - Created dynamic charts using Plotly  
   - Built interactive dashboards to track behavioral KPIs  

3. **Customer Lifetime Value Modeling**  
   - Estimated CLTV using tenure, spend, frequency  
   - Highlighted high-value customers in Power BI reports  

4. **Final Reporting**  
   - Compiled final Jupyter notebook with analysis + visuals  
   - Prepared Power BI dashboard export (PDF, Web View)  

## Week 5 Report

### 📊 Project Title: Integrated Modeling & Dashboard Finalization

#### 🧠 Key Objectives
- Optimize predictive model performance  
- Integrate all key metrics and models into a single interactive business dashboard  
- Prepare final deliverables for stakeholder presentation  

#### 🛠️ Tools Used
- Python (scikit-learn, SHAP)  
- Power BI  
- GridSearchCV for model tuning  

---

### 📌 Summary of Tasks:
1. **Model Optimization**  
   - Tuned Logistic Regression, XGBoost, and Neural Net models using `GridSearchCV`  
   - Evaluated performance with Precision, Recall, AUC, and ROC metrics  

2. **Feature Refinement**  
   - Conducted correlation analysis for multicollinearity detection  
   - Used SHAP values to interpret feature importance and model transparency  

3. **Dashboard Integration**  
   - Merged CLTV, churn prediction, and marketing response data into a single Power BI report  
   - Created filters and slicers for executive use (e.g., by age, education, tenure)  

4. **Report Export & Visualization**  
   - Enabled export options for PowerPoint and PDF  
   - Developed charts summarizing model comparisons and business KPIs  

5. **Final Report Compilation**  
   - Structured a comprehensive report including:
     - Project objectives and methodology  
     - Visual insights (dashboards and model plots)  
     - KPI summary and future scope  

---

### 🔭 Plans for Week 6:
- Deliver and present the capstone insights report  
- Participate in feedback and evaluation sessions  
- Document challenges, learnings, and improvement opportunities

### 📚 References:
- [Plotly Documentation](https://plotly.com/python/)  
- [Power BI Documentation](https://powerbi.microsoft.com/en-us/)  
- [scikit-learn Clustering](https://scikit-learn.org/stable/modules/clustering.html)  

---

> 🧑‍🎓 Student: Vyom Pandya  
> 🎓 Roll No: 22IT157  
> 🏢 Company: Agevole Innovation  
> 📅 Internship: Summer 2025  
> 📂 Project: Data Analytics
