
# 🚗 Insurance Risk and Claim Analysis | Power BI

An interactive **Power BI Business Intelligence project** focused on analysing insurance policy data, claim amounts, customer demographics and vehicle-related risk factors.

The project explores different aspects of insurance operations, including total policies, claim frequency, claim amounts, vehicle usage, coverage zones, customer demographics and factors associated with insurance claims.

The objective is to transform raw insurance data into meaningful insights that support insurance performance analysis, customer segmentation and risk assessment.

## 🎯 Project Objectives

- Analyse total insurance policies and claim amounts.
- Understand claim patterns across different customer segments.
- Compare insurance claims across vehicle makes and usage types.
- Analyse customer demographics and their relationship with claim amounts.
- Evaluate the impact of coverage zones and vehicle characteristics.
- Identify customer and vehicle segments associated with higher claim amounts.

## 📂 Dataset Overview

- **Dataset:** Insurance Policies Dataset
- **Source File:** `insurance_policies_data.xlsx`
- **Dataset Type:** Customer-level vehicle insurance data
- **Total Records:** 37,542
- **Total Columns:** 16
- **Unique Policy IDs:** 37,541

The dataset covers:

- Customer identification and birth dates
- Vehicle make, model and manufacturing year
- Vehicle colour and usage type
- Insurance coverage zones
- Customer education and gender
- Marital status and parent information
- Claim amounts and claim frequency
- Household income
- Number of children driving

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modelling, DAX and interactive dashboard development.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures, calculations and KPI development.
- **Excel** – Source dataset management.

## 🔄 Data Cleaning & Transformation

- Imported the Excel dataset into Power BI.
- Reviewed column names, data types and table structure.
- Checked missing values across all columns.
- Checked duplicate records.
- Corrected data types for numerical, categorical and date columns.
- Reviewed important fields such as ID, Claim Amount and Claim Freq.
- Prepared customer and vehicle attributes for analysis.
- Created calculated fields and measures to support reporting.

## 🏗️ Data Modelling

Organised the insurance dataset using the following structure:

**Main Data Table**

- `insurance_data_car` – Contains customer information, vehicle details, insurance coverage, claim amounts and claim frequency.

**Supporting Calculation Tables**

- `CALCULATED MEASURE` – Stores calculated measures used for KPI reporting and analysis.
- `Selected measure` – Supports dynamic measure selection within the report.

## 📊 Key DAX Measures

- Total Policies
- Total Claim Amount
- Average Claim Amount
- Male Count
- Female Count

Advanced DAX and Power BI features:

`CALCULATE()` · `DISTINCTCOUNT()` · `DIVIDE()` · `SUM()` · `AVERAGE()` · `FILTER()` · `Field Parameters`

## 📈 Power BI Dashboard

### Insurance Risk and Claim Analysis

The dashboard provides an interactive overview of insurance policies and claim-related performance.

**Key Analysis Areas:**

- Total insurance policies.
- Total claim amount.
- Average claim amount.
- Claim amount by vehicle usage (Private and Commercial).
- Claim amount by car make.
- Claim amount by coverage zone.
- Claim analysis by customer age group.
- Claim amount by number of children driving.
- Claim amount by education and marital status.
- Claim amount trends across vehicle manufacturing years.
- Customer gender-based analysis.

**Visualisations Used:**

- KPI Cards
- Donut Charts
- Clustered Bar Charts
- Clustered Column Charts
- Ribbon Charts
- Pie Charts
- Stacked Area Charts
- Matrix/Table Visuals
- Interactive Slicers

## 💡 Key Business Insights

| KPI | Result |
|---|---:|
| Total Records | 37,542 |
| Unique Policy IDs | 37,541 |
| Total Claim Amount | 187.82 Million |
| Average Claim Amount | 5,002.85 |
| Total Claim Frequency | 19,158 |
| Private Vehicle Records | 30,060 |
| Commercial Vehicle Records | 7,482 |

- Private vehicle records account for approximately 80.1% of the dataset.
- Commercial vehicle records account for approximately 19.9%.
- The dataset contains 37,541 unique IDs across 37,542 records.
- Ford has the highest number of records among the listed vehicle manufacturers, with 3,302 records.
- Claim amounts can be compared across coverage zones, vehicle manufacturers and customer demographics to identify patterns for further investigation.

*Note: These are descriptive findings from the dataset. Relationships between customer or vehicle attributes and claim amounts should not be interpreted as proof of causation.*

## 🎛️ Power BI Features

- Interactive KPI cards and charts.
- Dynamic measure selection using Field Parameters.
- Customer demographic analysis.
- Vehicle-wise claim analysis.
- Coverage zone comparisons.
- Claim amount distribution analysis.
- Interactive filtering and report exploration.
- Multiple visualisation types for business insights.

## 📁 Project Structure

```text
Insurance-Risk-and-Claim-Analysis/
│
├── Dataset/
│   └── insurance_policies_data.xlsx
│
├── PowerBI/
│   └── insurance.pbix
│
└── README.md
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open the `PowerBI` folder.
3. Open `insurance.pbix` using Power BI Desktop.
4. Update the Excel source file path if required.
5. Refresh the dataset.
6. Explore the dashboard using interactive visuals and filters.

## 👨‍💻 Author

**Devaprakash**

B.Tech Graduate in Artificial Intelligence and Data Science

Aspiring Data Analyst | Power BI | SQL | Python | Excel

---

⭐ If you find this project useful, consider giving this repository a star!
# Claim-and-Insurance-Analysis-Dashboard
