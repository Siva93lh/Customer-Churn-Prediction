# Customer-Churn-Prediction

# Customer-Churn-Prediction-Project

---

## 🔗 Project Links

- 📊 [Customer Churn ML Models](https://colab.research.google.com/drive/13hBAubQBbm6Whr5fHLgRAQ_lg0aPaeL-?usp=sharing)
- 🚀 [PowerBI Dashboards Dashboards](https://drive.google.com/file/d/14LlVrCxaG92v1JsayPidClMwJTFIAm9L/view?usp=sharing)
- 🤖 [Stremalit dashbaords](https://drive.google.com/file/d/1gNa_dULWRLk7h_qztCFwIfUTGWd1i2_w/view?usp=sharing)
- 📄 [Project Documentation](https://drive.google.com/file/d/14LlVrCxaG92v1JsayPidClMwJTFIAm9L/view?usp=sharing)


# 📌 INTRODUCTION

Customer Churn Prediction is a data analytics and machine learning project designed to identify customers who are likely to stop using a company's services and improve customer retention. The project uses customer data, service details, billing information, and machine learning model performance metrics to analyze churn patterns and support data-driven decision-making. Also analyzed customer demographics, contract types, monthly charges, tenure, and service usage patterns to identify important features that contribute to churn prediction.

# 🎯 OBJECTIVES

- **Identify Churn Customers:** Identify customers who are likely to stop using the company's services.
- **Analyze Customer Trends:** Examine customer tenure, service usage, and historical churn patterns.
- **Evaluate Contract Types:** Analyze churn rates across different contract types and service plans.
- **Monitor Customer Risks:** Identify customer segments associated with high churn rates.
- **Analyze Feature Importance:** Determine the key factors influencing customer churn predictions.
- **Evaluate Model Performance:** Assess machine learning models using appropriate evaluation metrics.
- **Develop Interactive Dashboards:** Create Power BI and Streamlit dashboards for effective churn analysis and visualization.
- **Support Customer Retention:** Provide actionable insights to improve customer satisfaction and reduce churn.

# 🚀 Project Resources

## 📊 Dashboards

- 🔗 [Power BI Dashboard](https://drive.google.com/file/d/1H6FNgb7bM_xFn-NQGNp_OY4qTnIEZJ0R/view?usp=sharing)
- 🌐 [Streamlit Dashboard](https://drive.google.com/file/d/1gNa_dULWRLk7h_qztCFwIfUTGWd1i2_w/view?usp=sharing)

## 📄 Project Documentation

- 📑 [View Project Documentation PDF](https://drive.google.com/file/d/14LlVrCxaG92v1JsayPidClMwJTFIAm9L/view?usp=sharing)

## 📁 Datasets

- 📂 [Customer Churn Prediction Dataset](https://drive.google.com/file/d/1bWJFAhrBSruSJdWA_q1IjetP8B2mF-yP/view?usp=sharing)
- 📂 [Customer Churn Analysis Dataset](https://drive.google.com/file/d/1_iq2aAr6E9gjzJ0AiZv54FZIadi7CwB2/view?usp=sharing)
- 📂 [ML Model Performance Dataset](https://drive.google.com/file/d/1_iq2aAr6E9gjzJ0AiZv54FZIadi7CwB2/view?usp=sharing)
- 📂 [Customer Retention Dataset](https://docs.google.com/spreadsheets/d/1XoUZ3waIQ82Gszhde1Dgwn3ckJE3_8sy/edit?usp=sharing&ouid=116913806936212812012&rtpof=true&sd=true)
- 📂 [Customer Risk Analysis Dataset](https://docs.google.com/spreadsheets/d/18mN2rle0xNzaMMeFFh0BA7U-Z2MM29Yg/edit?usp=sharing&ouid=116913806936212812012&rtpof=true&sd=true)
- 📂 [Customer Churn Summary Dataset](https://docs.google.com/spreadsheets/d/1p2SGgRr-oFCca7fs803VYkI2eFkzcvkq/edit?usp=sharing&ouid=116913806936212812012&rtpof=true&sd=true)


## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Machine Learning
- Microsoft Excel
- Power BI
- Power Query
- DAX
- Streamlit
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

### 🤖 **Machine Learning Models Used in Customer Churn Prediction**

- 🔹 Logistic Regression
- 🔹 Decision Tree Classifier
- 🔹 Random Forest Classifier
- 🔹 Gradient Boosting Classifier
- 🔹 Support Vector Machine (SVM)
- 🔹 K-Nearest Neighbors (KNN)
- 🔹 XGBoost Classifier
- 🔹 Naive Bayes Classifier

### 📊 **Evaluation Metrics Used**

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- F1-Score
- ROC-AUC Score

### 📊 **DAX Measures Used:**

- Total Customers = DISTINCTCOUNT('Customer Churn'[CustomerID])
- Churned Customers = CALCULATE(DISTINCTCOUNT('Customer Churn'[CustomerID]), 'Customer Churn'[Churn] = "Yes")
- Retained Customers = CALCULATE(DISTINCTCOUNT('Customer Churn'[CustomerID]), 'Customer Churn'[Churn] = "No")
- Total Churn Rate (%) = DIVIDE([Churned Customers], [Total Customers], 0) * 100
- Customer Retention Rate (%) = DIVIDE([Retained Customers], [Total Customers], 0) * 100
- Average Monthly Charges = AVERAGE('Customer Churn'[MonthlyCharges])
- Total Monthly Revenue = SUM('Customer Churn'[MonthlyCharges])
- Average Customer Tenure = AVERAGE('Customer Churn'[TenureMonths])
- Average Total Charges = AVERAGE('Customer Churn'[TotalCharges])
- High-Risk Customers = CALCULATE(DISTINCTCOUNT('Customer Risk Analysis'[CustomerID]), 'Customer Risk Analysis'[RiskCategory] = "High")
- Medium-Risk Customers = CALCULATE(DISTINCTCOUNT('Customer Risk Analysis'[CustomerID]), 'Customer Risk Analysis'[RiskCategory] = "Medium")
- Low-Risk Customers = CALCULATE(DISTINCTCOUNT('Customer Risk Analysis'[CustomerID]), 'Customer Risk Analysis'[RiskCategory] = "Low")
- Average Churn Risk Score = AVERAGE('Customer Risk Analysis'[ChurnRiskScore])
- Average Model Accuracy (%) = AVERAGE('ML Model Performance'[Accuracy]) * 100
- Average Model Precision (%) = AVERAGE('ML Model Performance'[Precision]) * 100
- Average Model Recall (%) = AVERAGE('ML Model Performance'[Recall]) * 100
- Average Model F1-Score (%) = AVERAGE('ML Model Performance'[F1Score]) * 100
- Best Model ROC-AUC (%) = MAX('ML Model Performance'[ROC_AUC]) * 100

## 📁 Repository Structure

```text
Customer-Churn-Prediction/
│
├── 📂 Dataset/
│   ├── Customer_Churn_Prediction_Dataset.xlsx
│   ├── Customer_Churn_Analysis_Dataset.xlsx
│   ├── ML_Model_Performance_Dataset.xlsx
│   ├── Customer_Retention_Dataset.xlsx
│   ├── Customer_Risk_Analysis_Dataset.xlsx
│   └── Customer_Churn_Summary_Dataset.xlsx
│
├── 📂 Machine_Learning/
│   └── Customer_Churn_Prediction_Model.ipynb
│
├── 📂 PowerBI/
│   └── Customer_Churn_Dashboard.pbix
│
├── 📂 Streamlit/
│   └── app.py
│
├── 📂 Documentation/
│   └── Customer_Churn_Project_Documentation.pdf
│
├── 📂 Screenshots/
│   ├── Customer_Churn_Dashboard.png
│   ├── Customer_Risk_Dashboard.png
│   └── ML_Model_Performance.png
│
├── requirements.txt
└── README.md
```

## 📌 Conclusion

- The Customer Churn Prediction project integrates Data Analytics, Machine Learning, Power BI, DAX, and Streamlit to support customer churn identification and retention analysis.
- The project transforms raw customer data into meaningful business insights through data preprocessing, exploratory data analysis (EDA), and churn pattern analysis.
- The machine learning component helps identify customers who are likely to leave and evaluate churn prediction performance.
- Customer contract, tenure, payment method, and service analysis help identify churn patterns across different customer segments.
- Feature importance analysis highlights the factors that contribute to customer churn predictions.
- Power BI provides interactive dashboards with KPIs, churn trends, customer distribution, and risk indicators.
- Streamlit provides a user-friendly interface for exploring churn insights, customer risk, and analytical results.
- The project demonstrates how data analytics and machine learning can support customer retention, risk assessment, and informed business decision-making.

## 🎯 Key Learnings

- **Data Preprocessing:** Learned to clean, transform, and prepare customer datasets for analysis.
- **Exploratory Data Analysis:** Gained insights into customer churn patterns, customer behavior, and risk indicators.
- **Machine Learning:** Understood how classification models can be used to predict potential customer churn.
- **Feature Importance:** Learned to identify important variables influencing customer churn predictions.
- **Model Evaluation:** Gained experience evaluating model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- **DAX Measures:** Developed measures to calculate churn rates, customer counts, revenue, and customer risk KPIs.
- **Power BI Visualization:** Learned to build interactive dashboards for monitoring churn trends and customer segments.
- **Streamlit Development:** Gained experience presenting churn predictions and analytical results through an interactive web application.
- **Business Intelligence:** Improved the ability to translate analytical findings into actionable customer retention strategies.
- **End-to-End Project Development:** Gained practical experience combining data analytics, machine learning, visualization, and reporting in one project.



