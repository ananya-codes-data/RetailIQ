# RetailIQ

End-to-End Retail Intelligence &amp; Customer Analytics Platform

## Business Background

Leadership has visibility into total revenue but lacks a clear read on which customers drive sustainable growth, and which high-value customers are at risk of churning.

## Business Problem

- Is the business growing sustainably?
- Are we retaining valuable customers?
- Which customers/products are we over-reliant on?
- Where's the growth opportunity?

## Dataset & Tools

- **Data:** Online Retail II dataset (UCI) — transaction-level records of a UK-based online retailer, spanning [01-12-2009 to 09-12-2011], covering invoices, products, quantities, prices, and customer/country info
- **Tools:** SQL (RFM, cohort, and concentration analysis)
→ Python (segmentation, churn flagging)
→ Power BI (dashboarding)

## Repository Structure

```text
RetaiIQ/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   └── online_retail_II.xlsx
|   |
|   ├── interim/
|   |   └── cleaned_retail_transactions.csv
|   |       
│   └── processed/
│       └── retail_transactions_enriched.csv     
│
├── notebooks/                                  
│   ├── 01_data_profiling.ipynb
│   ├── 02_data_cleaning_and_validation.ipynb          
│   └── 03_feature_engineering.ipynb          
│
├── dashboards/
│   └── retail_store_dashboard.pbix          
│
├── reports/                                    
│   ├── business_impact_summary.md              
│   └── executive_summary.md              
│
└── docs/
    └── data_dictionary.md                     
```
