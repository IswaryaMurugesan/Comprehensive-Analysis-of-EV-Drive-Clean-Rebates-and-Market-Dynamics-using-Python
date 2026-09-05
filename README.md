# Comprehensive Analysis of EV Drive Clean Rebates and Market Dynamics (2017–2026) Using Python

## 📌 Project Overview

This project presents a comprehensive analysis of **Electric Vehicle (EV) Drive Clean Rebate transactions from 2017 to 2026** using Python.

The analysis focuses on understanding EV adoption trends, rebate patterns, vehicle powertrain distribution, geographic concentration, environmental benefits, seasonal patterns, and brand-level efficiency.

The project uses data from the **Official Government Open Data Portal / NYSERDA** and applies Python-based data cleaning, transformation, exploratory data analysis, statistical analysis, visualization, and business interpretation.

---

## 🎯 Business Objective

The key objective of this project is to analyze EV rebate transaction data and identify meaningful patterns that can support:

* EV adoption and market trend analysis
* Rebate and incentive evaluation
* Environmental impact assessment
* Geographic targeting
* Brand and vehicle-model analysis
* Seasonal demand planning
* Data-driven policy and business decisions

---

## 📊 Dataset Overview


Source: Official Government Open Data Portal / NYSERDA

Dataset: EV Drive Clean Rebate Transactions

Time Period: 2017–2026

Raw Dataset: 239,278 rows × 11 columns

The dataset contains EV rebate transaction information along with vehicle, manufacturer, location, rebate, GHG reduction, and petroleum reduction details.

Due to the large size of the original dataset, it could not be uploaded directly to GitHub.

Dataset Link:

https://drive.google.com/drive/folders/12AqCaWCkcCGhf-NergYPSskr4wW4oLji?usp=sharing




| Metric                    |   Value |
| ------------------------- | ------: |
| Initial Records           | 239,278 |
| Initial Columns           |      11 |
| Duplicate Records Removed |  13,845 |
| Invalid Records Removed   |       5 |
| Final Analytical Records  | 225,428 |
| Unique ZIP Codes          |   1,644 |
| Manufacturers             |      34 |
| Vehicle Models            |     148 |
| Counties                  |      62 |

The dataset was cleaned and validated before performing the analytical stages.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization

---

## 🧹 Data Cleaning & Preparation

The raw dataset contained missing values, duplicate transactions, and invalid records.

The data preparation process included:

* Inspecting dataset structure and data types
* Identifying missing values
* Removing exact duplicate records
* Handling missing categorical information
* Identifying invalid rebate records
* Removing negative petroleum-reduction values
* Creating derived analytical features
* Validating the final dataset

After cleaning, the final analytical dataset contained **225,428 unique records with no remaining missing values**.

---

## 📈 Key Findings

### 1. EV Adoption Trend

EV rebate transactions increased substantially over the analysis period.

Annual transaction volumes:

| Year | EV Transactions |
| ---- | --------------: |
| 2017 |           4,532 |
| 2018 |           7,562 |
| 2019 |           8,167 |
| 2020 |          13,750 |
| 2021 |          21,173 |
| 2022 |          28,710 |
| 2023 |          43,199 |
| 2024 |          44,702 |
| 2025 |          40,136 |
| 2026 |          13,497 |

The trend shows strong EV adoption growth through the period, with the highest recorded annual volume occurring in **2024**.

---

### 2. BEV vs PHEV Distribution

The final dataset contains:

* **BEV:** 150,664 records (66.8%)
* **PHEV:** 74,764 records (33.2%)

This indicates that battery electric vehicles represent the majority of rebate transactions in the analyzed dataset.

---

### 3. Rebate Analysis

The rebate distribution is concentrated around lower-value incentives.

**Key statistics:**

* Mean rebate: **$885.01**
* Median rebate: **$500**
* Mode rebate: **$500**
* Rebate skewness: **1.1299**

Rebate tiers:

| Incentive Tier    | Transactions |
| ----------------- | -----------: |
| Low (≤ $500)      |      150,302 |
| Mid ($501–$1,100) |       25,480 |
| High (> $1,100)   |       49,646 |

The difference between the mean and median indicates that higher-value rebates influence the overall average.

---

### 4. Environmental Impact

The analysis estimated environmental benefits associated with EV adoption.

**Average annual impact per vehicle:**

* Petroleum reduction: **518.51 gallons**
* GHG reduction: **2.44 MT CO₂e**

Environmental impact classification:

| Impact Tier   | Transactions |
| ------------- | -----------: |
| Low Impact    |       39,050 |
| Medium Impact |      186,353 |
| High Impact   |           25 |

Approximately **82.7%** of records fall within the Medium Impact category.

---

### 5. Petroleum Savings Efficiency

The project calculated petroleum savings efficiency as:

**0.793 gallons saved per rebate dollar**

Brand-level analysis was also performed to compare petroleum savings efficiency across leading EV manufacturers.

This provides a useful perspective for evaluating incentive effectiveness alongside environmental outcomes.

---

### 6. Geographic Concentration

The dataset covers **62 counties** and **1,644 unique ZIP identifiers**.

A notable concentration was observed in **Nassau County**, which accounted for **39,255 transactions**.

The geographic analysis can help identify regions where EV adoption is already strong and areas where additional infrastructure or targeted incentive programs may be beneficial.

---

### 7. Seasonal Patterns

Monthly transaction analysis indicates seasonal variation in EV rebate activity.

* Lower activity was observed during **January and February**
* Activity generally increased during the **spring and summer months**

This pattern can support operational planning, campaign timing, and resource allocation.

---

### 8. Market Concentration

The analysis identified significant concentration around certain manufacturers and models.

* **Tesla:** 106,886 transactions
* **Tesla Model Y:** 64,704 transactions

This highlights the importance of considering brand and model concentration when evaluating the overall EV market.

---

## 📌 Statistical Insights

Correlation analysis showed a very strong relationship between:

* **GHG reduction**
* **Petroleum reduction**

The correlation matrix reported a value of approximately **1.00** between these environmental measures.

In comparison, rebate amount showed much weaker relationships with the environmental measures, suggesting that incentive size alone does not fully explain environmental outcomes.

---

## 💡 Business Recommendations

### 1. Introduce Efficiency-Linked Incentives

Consider designing tiered or efficiency-linked incentives that reward vehicles based on measurable environmental benefits rather than relying only on fixed rebate amounts.

### 2. Reduce Market Concentration

The strong concentration around Tesla and specific vehicle models suggests an opportunity to encourage broader manufacturer participation and diversify EV adoption.

### 3. Use Geographic Targeting

County and ZIP-level analysis can help identify regions requiring:

* EV charging infrastructure
* Awareness campaigns
* Targeted incentives
* Equitable EV adoption programs

### 4. Optimize Seasonal Operations

Because transaction activity varies by month, staffing, campaign planning, and operational resources can be aligned with periods of higher EV adoption activity.

---

## 📂 Project Files

### 📓 Python Analysis

`EV_Drive_Clean_Rebates_Analysis.ipynb`

Contains the complete Python workflow including:

* Data inspection
* Data cleaning
* Feature engineering
* EDA
* Statistical analysis
* Visualization
* Business insights

### 📄 Project Report

`EV_Drive_Clean_Rebates_Project_Report.pdf`

A concise professional report summarizing the methodology, findings, visualizations, and recommendations.

---

## 🔍 Project Outcome

This project demonstrates how Python can be used to transform a large government EV rebate dataset into actionable business and environmental insights.

The analysis combines **data cleaning, exploratory analysis, statistical interpretation, visualization, and business recommendations** to understand EV adoption and rebate dynamics from 2017–2026.

---

## 👩‍💻 Author

**Iswarya Murugesan**

Aspiring Data Analyst | Python | SQL | Power BI | Excel

📍 Chennai, India
