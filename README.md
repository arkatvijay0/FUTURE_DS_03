# 📊 Bank Marketing Campaign & Conversion Performance Analysis

## Future Interns – Data Science & Analytics Task 3

### 📌 Project Overview

This project analyzes the performance of a bank marketing campaign to understand customer conversion patterns, campaign effectiveness, contact-channel performance, and customer segments.

The analysis focuses on identifying where conversions occur, which customer segments perform better, which communication channels are more effective, and how campaign outcomes vary across different customer characteristics.

The project combines Python-based exploratory data analysis with an interactive Power BI dashboard to convert raw marketing data into meaningful business insights.

---

## 🎯 Project Objectives

- Analyze overall customer conversion performance
- Calculate conversion and non-conversion rates
- Identify high-performing contact channels
- Analyze conversion performance across customer segments
- Compare campaign outcomes
- Analyze previous campaign performance
- Identify important conversion trends
- Provide actionable business recommendations

---

## 📂 Dataset

The project uses the **Bank Marketing dataset** containing customer demographic information, financial attributes, contact details, campaign information, previous campaign outcomes, and the final campaign response.

### Dataset Size

- **45,211 customer records**
- **17 original variables**
- Additional derived features were created during analysis.

### Main Variables

- `age` – Customer age
- `job` – Customer occupation
- `marital` – Marital status
- `education` – Education level
- `balance` – Customer account balance
- `housing` – Housing loan status
- `loan` – Personal loan status
- `contact` – Contact communication type
- `month` – Month of contact
- `campaign` – Number of contacts during the campaign
- `poutcome` – Previous campaign outcome
- `y` – Original campaign response

---

## 🧹 Data Preparation

The dataset was examined and prepared for analysis through:

- Data type verification
- Duplicate checking
- Missing/unknown value assessment
- Categorical-value inspection
- Feature engineering
- Conversion variable preparation

Additional analytical features were created, including:

- Age groups
- Campaign contact groups
- Previous-contact indicator
- Month number

---

## 📊 Key KPIs

The final analysis identifies the following major campaign metrics:

| KPI | Value |
|---|---:|
| Total Customers | 45.21K |
| Total Conversions | 5.29K |
| Conversion Rate | 11.70% |
| Non-Conversions | 39.92K |
| Drop-off Rate | 88.30% |

---

## 📈 Power BI Dashboard

The project contains a three-page interactive Power BI dashboard.

### Page 1 – Executive Overview

Provides an overall view of:

- Total customers
- Total conversions
- Conversion rate
- Non-conversions
- Conversion funnel
- Contact-channel performance
- Monthly conversion trends

### Page 2 – Channel & Campaign Performance

Analyzes:

- Conversion rate by contact channel
- Conversions by contact channel
- Customer campaign outcomes
- Previous campaign outcomes
- Key campaign insights

### Page 3 – Customer Segments & Conversion Trends

Analyzes conversion performance across:

- Age groups
- Education levels
- Occupations
- Marital status
- Housing and loan status

---

## 🔍 Key Insights

- The overall campaign conversion rate is approximately **11.70%**.
- The majority of contacted customers did not convert.
- Cellular contact has the strongest conversion rate among the major contact channels.
- Conversion performance varies across age groups.
- Customer occupation and education are associated with differences in conversion performance.
- Conversion rates vary across marital, housing, and loan segments.
- Previous campaign outcomes provide useful information for understanding customer response.
- Monthly conversion performance varies across the campaign period.

---

## 💡 Business Recommendations

1. Prioritize high-performing communication channels for future campaigns.

2. Develop targeted marketing strategies for customer segments with stronger conversion rates.

3. Use customer demographics and campaign history to improve targeting.

4. Optimize campaign timing based on observed monthly conversion patterns.

5. Reduce unnecessary repeated contacts and focus resources on customers with stronger conversion potential.

6. Use previous campaign outcomes to improve follow-up and customer prioritization.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
- **Microsoft Power BI**
- **Git & GitHub**

---

## 📁 Project Structure

```text
Bank-Marketing-Campaign-Analysis/
│
├── dataset/
│   ├── raw/
│   └── processed/
│
├── notebook/
│   └── bank_marketing_analysis.ipynb
│
├── dashboard/
│   └── Bank_Marketing_Campaign_Analysis.pbix
│
├── images/
│   ├── Executive_Overview.png
│   ├── Channel_Campaign_Performance.png
│   └── Customer_Segments_Trends.png
│
├── report/
│   └── Bank_Marketing_Analysis_Report.pdf
│
└── README.md
