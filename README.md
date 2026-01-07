# 📊 Marketing Campaign Effectiveness Analysis  
## A/B Testing, Regression & Time Series Analysis

---

## 📌 Project Overview
Organizations often invest heavily in multiple digital advertising platforms without clear analytical evidence of which channel delivers the highest **Return on Investment (ROI)**.

In this project, parallel marketing campaigns were executed on **Facebook Ads** and **Google Ads (AdWords)** to drive customer conversions.  
Despite comparable budget allocation, decision-makers lacked clarity on which platform performed better in terms of **engagement, cost efficiency, conversion performance, and revenue generation**.

This project applies **data-driven analytical techniques** to evaluate campaign effectiveness and support **optimized marketing budget decisions** across global markets.

---

## 🎯 Business Objective
The primary objective is to determine which advertising platform—**Facebook Ads or Google Ads**—delivers superior performance and higher ROI.

This is achieved using:
- Exploratory Data Analysis (EDA)
- Campaign performance comparison
- A/B hypothesis testing
- Regression analysis to identify performance drivers
- Time series analysis to assess trends and stability over time

---

## 📂 Data Overview
The dataset contains **daily campaign-level data** for both advertising platforms, including:

- Impressions  
- Clicks  
- Conversions  
- Advertising Spend  
- Revenue  

### 📐 Derived Metrics
The following KPIs were calculated for deeper analysis:
- Click-Through Rate (CTR)
- Cost per Click (CPC)
- Cost per Acquisition (CPA)
- Conversion Rate
- Return on Investment (ROI)

---

## 🧪 Dataset Information
**Dataset Name:** `A_B_testing_dataset.csv`

The dataset includes user-level experimental data used for A/B testing, consisting of:
- `user_id`
- `group` (control / variant)
- `conversion`
- `revenue` (if applicable)

This data was used to evaluate experimental performance and statistical significance between groups.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted to understand data distribution, variability, and overall campaign behavior.

### Key EDA Activities
- Summary statistics for spend, clicks, conversions, and revenue  
- Platform-wise comparison of CTR, CPC, CPA, and ROI  
- Identification of outliers and anomalies  
- Visualization of metric distributions and trends  

EDA established baseline performance differences and guided further statistical testing.

---

## 📈 Campaign Performance Comparison
A comparative analysis evaluated Facebook Ads and Google Ads across critical marketing KPIs:

- Click-Through Rate (CTR)  
- Conversion Rate  
- Cost per Click (CPC)  
- Cost per Acquisition (CPA)  
- Return on Investment (ROI)  

This step provided a descriptive comparison of platform efficiency and effectiveness.

---

## 🧠 A/B Testing & Hypothesis Testing
Statistical hypothesis testing was applied to validate observed performance differences.

### Hypotheses
- **Null Hypothesis (H₀):**  
  There is no statistically significant difference in campaign performance between Facebook Ads and Google Ads.

- **Alternative Hypothesis (H₁):**  
  There is a statistically significant difference in campaign performance between Facebook Ads and Google Ads.

A two-sample statistical test was conducted at a **95% confidence level (α = 0.05)** on key metrics such as **conversion rate and CPA**.

---

## 📉 Regression Analysis
Regression modeling was used to identify factors influencing campaign success and ROI.

### Model Objectives
- Quantify the impact of platform choice and engagement metrics  
- Identify statistically significant drivers of conversions and ROI  

### Model Structure
**Dependent Variables**
- Conversions
- ROI

**Independent Variables**
- Advertising Platform (Facebook = 0, Google = 1)
- Advertising Spend
- Click Volume
- Cost per Click (CPC)
- Click-Through Rate (CTR)

Regression coefficients and p-values were analyzed to determine predictor significance.

---

## ⏳ Time Series Analysis
Time series analysis was performed to assess performance trends over time.

### Objectives
- Identify trends in clicks, conversions, and spend  
- Detect seasonality or fluctuations  
- Compare platform consistency and stability  

Daily metrics were analyzed to evaluate sustained campaign performance.

---

## 💡 Key Insights
- Statistically significant performance differences were identified between platforms  
- Platform selection, ad spend, and click volume strongly influenced conversions  
- Cost-efficiency metrics such as CPA had a direct impact on ROI  
- Time series trends revealed differences in performance consistency  

---

## ✅ Conclusion & Business Recommendations
By integrating **EDA, A/B testing, regression modeling, and time series analysis**, this project provides a comprehensive evaluation of digital marketing campaign performance.

The insights support **data-driven budget allocation**, enabling organizations to:
- Optimize advertising spend
- Improve conversion efficiency
- Maximize ROI across global markets

---

## 🛠 Tools & Skills Demonstrated
- Exploratory Data Analysis (EDA)
- A/B Testing & Hypothesis Testing
- Regression Analysis
- Time Series Analysis
- Marketing Analytics
- Business-Focused Data Interpretation

---

## 👤 Author
**Yashka**  
Data Analyst Aspirant  

