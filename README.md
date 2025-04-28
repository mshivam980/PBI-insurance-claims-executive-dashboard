# Insurance Claims Executive Dashboard

This repository contains a comprehensive Power BI dashboard for insurance claims analytics. The dashboard enables executives and analysts to monitor claim trends, profitability, processing efficiency, approval/rejection rates, and geographical distribution, all powered by real-world data.

https://github.com/user-attachments/assets/fe8759c9-1e2f-4838-a92d-d3a964ae8ea8

## Overview

- **Total Claims Submitted:** 10,000+
- **Total Premiums Collected:** $61M
- **Total Claims Pay-Out:** $84M
- **Profitability:** -$23M (-28%)
- **Average Approval Rate:** 33%
- **Average Rejection Rate:** 34%
- **Average Processing Time:** 50 days
- **SLA Compliance (30 days):** 27%

## Objectives

- Analyze trends in claims submission and payouts over time
- Evaluate profitability by comparing payouts with collected premiums
- Measure and improve claims processing times and SLA compliance
- Identify geographical and policy-based claim distributions
- Detect outliers and analyze approval/rejection patterns

## Files & Structure
.
├── data/
│ └── insurance_claims.xlsx
├── dashboard/
│ └── mshivam980-gmailcom.pbix
├── docs/
│ ├── Dashboard.pdf
│ └── Insurance-Claim-Case-Study.pdf
├── README.md
├── LICENSE
└── .gitignore

- **data/insurance_claims.xlsx:** Raw dataset (claims, policies, customers)
- **dashboard/mshivam980-gmailcom.pbix:** Power BI dashboard file
- **docs/Dashboard.pdf:** Sample dashboard and key metrics
- **docs/Insurance-Claim-Case-Study.pdf:** Problem statements, dataset schema, and visualization guidelines

## Power BI Dashboard Features

- **Dynamic KPIs:** Total claims, premiums, payouts, profit, approval/rejection rates, processing time, SLA compliance
- **Trends Over Time:** Monthly/quarterly/yearly claim and payout trends
- **Profitability Analysis:** By claim type, region, and over time
- **Processing Time Analysis:** Histogram, SLA compliance, outlier detection
- **Approval/Rejection Analysis:** Monthly rates, by claim type, interactive filtering
- **Geographical Breakdown:** Claims by region, state, city (hotspots highlighted)
- **Interactive Filters:** By claim type, policy type, region, time period

## Dataset Schema

### Claims Table

| Column Name           | Description                                                 |
|-----------------------|-------------------------------------------------------------|
| Claim ID              | Unique identifier for each claim                            |
| Claim Date            | Date when claim was filed                                   |
| Approval/Rejection Date | Date when claim was approved/rejected                      |
| Claim Amount          | Monetary value of the claim                                 |
| Processing Time       | Days between claim and decision                             |
| Policy Number         | Linked insurance policy                                     |
| Claimant ID           | Linked customer                                             |
| Claim Status          | Approved, Rejected, Pending, Under Review                   |

### Policies Table

| Column Name        | Description                                |
|--------------------|--------------------------------------------|
| Policy Number      | Unique policy identifier                   |
| Policy Type        | Health, Auto, Life, Property, etc.         |
| Claim Type         | Accident, Theft, Medical, Damage, etc.     |
| Premium Amount     | Policy premium                             |
| Policy Purchase Date| Policy start date                          |
| Claimant ID        | Linked customer                            |

### Customers Table

| Column Name | Description                    |
|-------------|--------------------------------|
| Claimant ID | Unique customer identifier     |
| Name        | Full name                      |
| Age         | Age in years                   |
| City/State/Region | Location                  |
| Gender      | Male/Female/Other              |

## Data Visualization Guidelines

- **Font:** Segoe UI (Titles: 14pt bold, Axis: 10pt bold, Labels: 9pt)
- **Color Palette:**  
  - Primary: #25476A (Chambray Blue)  
  - Secondaries: #AB47BC, #03A9F4, #9FCC2E, #FA9F1B
- **Layout:** Unified style for all charts (see `docs/Insurance-Claim-Case-Study.pdf` for full details)

## How to Use

1. **Clone the repository**
2. **Open `dashboard/mshivam980-gmailcom.pbix` in Power BI Desktop**
3. **If prompted, set the data source path to `data/insurance_claims.xlsx`**
4. **Explore the dashboard using interactive filters and visuals**

## References

- See `docs/Insurance-Claim-Case-Study.pdf` for detailed problem statements, data dictionary, and visualization standards.
- `docs/Dashboard.pdf` provides sample dashboard screenshots and KPIs.

## License

[MIT License](LICENSE)

