# Customer Churn Analysis using Power BI

## Project Objective
The objective of this project is to help businesses understand and reduce customer attrition. Using Power BI Desktop, the dashboards identify customers at risk of churning and highlight the factors that drive retention.

## Repository Contents
- `02 Customer Churn-Dataset.xlsx` – sample customer data used by the reports.
- `Customer Churn Dashboard.pbix` – overview dashboard focused on churn metrics.
- `Customer Risk Analysis Dashboard.pbix` – report exploring drivers of churn and customer risk.
- `Customer Churn Dashboard.png` – preview of the churn dashboard.
- `Customer Risk Analysis.png` – preview of the risk analysis dashboard.

## Dashboard Features
- **Predictive churn modeling** to proactively flag high-risk customers.
- **Customer segmentation** for tailored marketing and retention strategies.
- KPI cards and trend visuals for quick insight.
- Built entirely with Power BI Desktop and Excel.

## Getting Started
### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/).

### Clone the repository
```bash
git clone https://github.com/Pavankumarmanagoli/Customer-Churn-Analysis-using-Power-BI.git
cd Customer-Churn-Analysis-using-Power-BI
```

### Open the dashboards
1. Launch Power BI Desktop.
2. Open `Customer Churn Dashboard.pbix` or `Customer Risk Analysis Dashboard.pbix`.
3. Replace the sample dataset with your own data if desired.
4. Refresh the data to view updated insights.

#### Example DAX measure
```DAX
Churn Rate =
DIVIDE(
    CALCULATE(COUNTROWS(Customers), Customers[Churn] = "Yes"),
    COUNTROWS(Customers)
)
```

## Usage
- Use the **Customer Churn Dashboard** for a high-level overview of churn KPIs.
- Explore the **Customer Risk Analysis Dashboard** to understand the drivers behind churn.
- Combine insights to design data‑driven retention strategies.

## Dashboard Previews
![Customer Churn Dashboard](Customer%20Churn%20Dashboard.png)
![Customer Risk Analysis](Customer%20Risk%20Analysis.png)

## License
This project is licensed under the [MIT License](LICENSE).
