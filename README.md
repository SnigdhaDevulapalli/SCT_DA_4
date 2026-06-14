# 📊 Marketing Campaign Analysis using Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a marketing campaign dataset instead of building a Machine Learning model. The objective is to understand campaign performance, analyze customer conversion through the marketing funnel, and identify which marketing channels provide the highest Return on Investment (ROI).

---

## 🎯 Objective

* Clean and inspect the dataset.
* Perform Exploratory Data Analysis (EDA).
* Visualize the marketing funnel.
* Analyze channel performance and ROI.
* Recommend which marketing channels should receive more budget.

---

## 📂 Dataset

**Dataset:** `nykaa_campaign_data.csv`

The dataset contains information related to:

* Campaign Type
* Marketing Channel
* Impressions
* Clicks
* Leads
* Conversions
* Revenue
* Acquisition Cost
* ROI
* Date

---

## 🛠 Tools and Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📋 Data Cleaning

The following preprocessing steps were performed:

* Checked for missing values.
* Checked for duplicate records.
* Converted the Date column into datetime format.
* Verified data types.

---

## 📈 Exploratory Data Analysis

### Campaign Analysis

* Distribution of campaign types.
* Distribution of marketing channels.

### Revenue Analysis

* Revenue distribution.
* ROI distribution.

### Correlation Analysis

* Heatmap showing relationships among numerical variables.

### Marketing Funnel Analysis

Customer Journey:

```
Impressions
↓
Clicks
↓
Leads
↓
Conversions
```

### Channel Performance Analysis

* Average ROI by channel.
* Average revenue by channel.
* Average acquisition cost by channel.

---

## 📊 Visualizations

* Campaign Type Distribution
* Marketing Channel Distribution
* Revenue Distribution
* ROI Distribution
* Correlation Heatmap
* Marketing Funnel Chart
* Average ROI by Channel
* Average Revenue by Channel
* Acquisition Cost by Channel

---

## 🔍 Key Insights

* Customer count decreases from impressions to conversions.
* Revenue is positively related to clicks, leads, and conversions.
* Marketing channels exhibit different ROI values.
* High-performing channels generate greater returns with lower acquisition costs.

---

## 💡 Recommendations

* Allocate more budget to channels with the highest ROI.
* Optimize underperforming channels.
* Improve conversion rates to reduce customer drop-off within the marketing funnel.
* Focus on maximizing profitability through data-driven decisions.

---

## 📁 Project Structure

```text
Marketing-Campaign-EDA/
│
├── nykaa_campaign_data.csv
├── Marketing_Campaign_EDA.ipynb
└── README.md
```

---

## 🚀 How to Run

1. Open Jupyter Notebook.
2. Open `Marketing_Campaign_EDA.ipynb`.
3. Run all cells sequentially.
4. Explore the visualizations and insights generated from the analysis.

---

## 📌 Conclusion

Exploratory Data Analysis helped uncover important insights into campaign effectiveness and customer behavior. By focusing marketing investments on high-ROI channels, organizations can improve overall campaign performance and maximize returns.
