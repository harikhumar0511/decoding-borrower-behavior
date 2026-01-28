# Decoding Borrower Behavior: Lending Patterns & Loan Outcomes

## Project Overview
This project analyzes mortgage lending patterns and borrower outcomes in Massachusetts from 2020 to 2023 to understand who gets approved, who gets denied, and why. Using a Power BI–driven analytical approach, the project explores lending volume trends, borrower characteristics, loan purposes, and income-level dynamics that influence approval and denial decisions.

The goal is to translate complex lending data into clear, decision-ready insights for lenders, policymakers, and analytics teams.

---

## Key Business Questions
- How has mortgage lending volume changed over time in Massachusetts?
- Which loan types dominate the lending market?
- What factors most strongly drive loan approval and denial decisions?
- How does borrower income influence denial rates?
- Which loan purposes face the highest borrower friction?

---

## Data Sources
This project integrates multiple publicly available datasets, including:
- Massachusetts Loan Application Records (2020–2023)
- County-level mortgage lending summaries
- Massachusetts income and housing statistics (ACS)
- Freddie Mac Single-Family Loan-Level Data
- Fannie Mae Mortgage Performance Dataset

Due to data size and licensing constraints, raw datasets are not included in this repository. Insights are derived from aggregated and modeled data presented through Power BI dashboards and summary reports.

---

## Dashboard Structure (Power BI)

### Page 1 – Lending Landscape
- Lending volume trends over time
- Loan type distribution (Conventional, FHA, VA)
- Geographic concentration by county
- Purchase vs. refinance behavior

### Page 2 – Drivers of Approval
- Approval rate trends across years
- Impact of debt-to-income ratio and loan purpose
- Borrower demographic patterns
- Key approval thresholds and inflection points

### Page 3 – Denial Analysis
- Denial rate trends over time
- Income-based denial disparities
- Loan purposes with the highest rejection rates
- Primary drivers of loan denial

---

## Key Insights
- Mortgage approval rates declined from approximately 66% in 2020 to 55% in 2023, largely driven by rising interest rates
- Debt-to-income ratio emerged as the strongest predictor of approval and denial
- Borrowers earning under $50K consistently faced higher denial rates
- Home improvement loans experienced the highest borrower friction
- Denial patterns remained stable even as application volumes fluctuated

---

## Tools & Technologies
- Power BI (DAX, interactive dashboards)
- Python (data preprocessing and validation)
- Public mortgage and housing datasets
- Data storytelling and KPI-driven analysis

---

## Repository Structure
decoding-borrower-behavior/

├── powerbi/ # Power BI (.pbix) dashboard file

├── reports/ # presentation deck

└── README.md

# Notes on Power BI Access
The Power BI dashboard file (.pbix) is included in this repository.  
Dashboard visuals are presented in the PDF report and presentation files due to Power BI Desktop being Windows-only and requiring local installation.

## Why This Project Matters
This project demonstrates how lending data can be transformed into transparent, decision-ready insights that explain borrower outcomes, highlight systemic friction, and support data-informed lending strategies.
