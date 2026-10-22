# Audit Data Analytics: GL & AP Exception Detection

## Overview

This project is an educational audit analytics simulation based on synthetic financial transaction data.

The project represents a fictional Saudi retail company called **Namaa Retail Company**. It analyzes General Ledger and Accounts Payable data for the 2025 reporting period and identifies unusual transactions that may require further audit investigation.

The project does not use real company information, real invoices, real employees, or real financial records.

## Project Objective

The objective of this project is to demonstrate how audit data analytics can be used to:

- Analyze structured accounting data.
- Review General Ledger and Accounts Payable populations.
- Identify unusual or high-risk transactions.
- Detect potential duplicate supplier invoices.
- Review high-value and year-end transactions.
- Identify weekend and after-hours journal entries.
- Review missing supporting documentation.
- Identify potential cut-off issues.
- Document exceptions and recommended follow-up procedures.
- Present results in an executive memorandum.

## Dataset Summary

The project uses synthetic data created exclusively for educational and portfolio purposes.

The analysis includes:

- 500 fictional journal entries.
- 1,000 General Ledger lines.
- 300 Accounts Payable invoices.
- Fictional vendors, employees, invoices, journal entries, and transaction identifiers.
- Reporting period from 1 January 2025 to 31 December 2025.
- Currency: Saudi Riyal (SAR).

## Analytics Tests

The workbook includes documented tests for:

1. Duplicate supplier invoice numbers.
2. Potential duplicate invoice amounts.
3. High-value General Ledger and Accounts Payable transactions.
4. Year-end journal entries.
5. Friday and Saturday postings.
6. After-hours journal entries.
7. Round-number transactions.
8. Missing purchase orders and goods receipts.
9. Invoice-to-posting date differences.
10. Potential cut-off exceptions.
11. Unusual account combinations.
12. Unbalanced journal entries.
13. Potential segregation-of-duties conflicts.
14. Large or unusual manual journal entries.
15. Potential duplicate payments.

## Key Results

The completed workbook identified:

- **41 exception instances**
- **38 unique transaction keys**
- **5 high-priority exceptions**
- **15 documented analytics tests**
- **0 confirmed simulated errors in the baseline exception register**

These results represent screening indicators only. They do not represent confirmed financial statement misstatements, fraud, or audit conclusions.

## Main Deliverables

### Excel Workbook

[Open the Audit Analytics Workbook](Audit_Data_Analytics_2025.xlsx)

The workbook includes:

- Project overview and instructions.
- Centralized parameters and screening thresholds.
- Synthetic General Ledger data.
- Synthetic Accounts Payable data.
- Analytics test catalog.
- Traceable exception register.
- Executive dashboard.
- Audit memo summary.
- Internal quality-control validation information.

### Executive Memorandum

[Open the Executive Board Memorandum](Executive_Board_Memo_EN.docx)

The memorandum summarizes:

- Executive results.
- Scope and methodology.
- Principal risk indicators.
- The role of the Excel workbook.
- Recommendations to management.
- Project limitations.
- Overall conclusion.

## Methodology

The project follows this workflow:

```text
Data Preparation
        ↓
Data Quality Validation
        ↓
Risk-Based Test Design
        ↓
Exception Detection
        ↓
Evidence and Follow-Up Planning
        ↓
Evaluation and Reporting
Each test considers:
The risk being addressed.
The relevant audit assertion.
The data source.
The screening rule or threshold.
The interpretation of the result.
The evidence required.
The recommended follow-up procedure.
Exception Handling Approach
An exception is treated as a transaction or pattern that triggers a screening rule.
The project distinguishes between:
Flagged anomaly: A transaction triggered an analytics rule.
Potential exception: The transaction requires further investigation.
Confirmed error: Evidence supports that the accounting treatment is incorrect.
Potential misstatement: An identified error may affect a financial statement amount.
Fraud: A serious conclusion that cannot be inferred from an analytics flag alone.
The project does not classify flagged transactions as fraud or confirmed errors without supporting evidence.
Tools Used
Microsoft Excel-compatible workbook.
Excel formulas and structured tables.
Filters and conditional formatting.
Executive dashboard and charts.
Synthetic data generation.
Audit documentation and memorandum preparation.
Skills Demonstrated
General Ledger analysis.
Accounts Payable testing.
Audit data analytics.
Audit assertion awareness.
Risk-based test design.
Duplicate invoice screening.
Cut-off and year-end testing.
Data-quality validation.
Exception documentation.
Excel formulas and structured tables.
Dashboard reporting.
Professional business communication.
Important Disclaimer
This project is an educational audit analytics simulation using synthetic transaction data.
The company, vendors, employees, invoices, journal entries, transactions, and exceptions are fictional and do not represent actual records of a real company.
An identified anomaly does not, by itself, establish fraud or a financial statement misstatement.
This project is not an actual audit or assurance engagement and does not express an audit opinion.
Limitations
The underlying data are synthetic.
No real company ledger was accessed.
No actual supplier invoices or bank records were reviewed.
No external confirmations were obtained.
The duplicate-payment test is limited because no separate payment register was provided.
The cut-off test is illustrative because a complete subsequent-period population was not included.
Screening thresholds are educational assumptions and are not approved audit materiality levels.
Intended Use
This project was prepared as an educational portfolio project to demonstrate accounting, audit analytics, Excel, data analysis, exception reporting, and professional documentation skills.
It is intended for learning, interview discussion, and portfolio presentation only.
