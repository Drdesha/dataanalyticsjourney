📊 Loan Insights Dashboard (Looker / BigQuery)
📌 Overview
This dashboard provides a high-level view of loan portfolio health, designed to support risk monitoring, financial oversight, and strategic decision-making. It consolidates loan performance metrics into a single executive-facing view.
The dashboard was built using Google BigQuery as the analytical backend and Looker for visualization and reporting.
🔍 Key Metrics & Visuals
1. Total Amount of Outstanding Loans
Displays the total dollar value of all active outstanding loans
Current portfolio exposure: $3.08B
Enables leadership to quickly assess overall credit exposure
2. Percentage of Outstanding Loans (Loan Status Breakdown)
Visualizes loan performance by status:
Current
Charged Off
Late (16–30 days, 31–120 days)
In Grace Period
Default
Highlights portfolio risk concentration and early warning signals
3. Total Count of Outstanding Loans by State
Geographic distribution of loan volume
Supports regional risk assessment and compliance analysis
Enables identification of states with disproportionately high loan activity
4. Top 10 Customers by Highest Income
Shows highest-income borrowers alongside:
Interest rate
State
Home ownership status
Useful for understanding borrower profiles and pricing dynamics
🛠️ Technical Implementation
Data Source: Structured loan and customer data in BigQuery
Modeling: Metrics and dimensions defined using LookML
Visualizations: Tiles built for KPIs, tables, and pie charts
Refresh Strategy: Designed to support scheduled refreshes for near-real-time monitoring
💡 Business Value
This dashboard enables stakeholders to:
Monitor portfolio risk at a glance
Identify delinquency trends early
Support credit policy and pricing decisions
Understand regional and customer-level exposure

## 📸 Dashboard Preview
![Loan Insights Dashboard](screenshots/loaninsights_dashboard_012626.png)
## 📊 Analytics Projects

### Loan Insights Dashboard
Executive-level loan portfolio dashboard built with BigQuery and Looker.  
➡️ [View Project](loan-insights-dashboard/)
