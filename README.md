EAST Finance Pro — Power BI Financial Dashboard






📊 Project Overview

EAST Finance Pro is an interactive financial analysis dashboard developed in Microsoft Power BI.
The project transforms financial statement data into an executive-friendly analytical report covering revenue, profitability, cash flow, assets, liabilities, equity, and financial ratios.

The dashboard is designed to help users quickly understand financial performance across different periods and identify important changes in profitability, liquidity, leverage, and returns.

🎯 Project Objectives

Analyze company financial performance over time.

Monitor revenue, costs, operating income, and net income.

Track gross and operating profitability.

Analyze operating cash flow and free cash flow.

Evaluate the company's balance sheet position.

Monitor assets, liabilities, debt, cash, inventory, and equity.

Calculate and visualize key financial ratios.

Provide interactive year and period filtering.

Present complex financial information through clear executive-level visuals.

📑 Dashboard Pages

1. Introduction

The Introduction page provides a high-level overview of the company's financial performance.

Key metrics and analysis include:

Revenue

Total Assets

Gross Margin %

Net Margin %

SG&A

Operating Income

Net Income

EPS (Basic)

Gross Profit

Revenue trends by quarter

Net income trends

Yearly financial comparisons

Main visuals:

KPI cards

Revenue and margin trend charts

Operating Income vs. Net Income

Revenue / Net Income / EPS analysis

Gross Profit trend

Year slicer

Quarterly analysis

2. Profitability and Cash

This page focuses on profitability performance and cash generation.

Key metrics include:

Revenue

Cost of Revenue

SG&A

Operating Income

Net Income

Operating Margin %

SG&A % of Revenue

Operating Cash Flow

Free Cash Flow

Main visuals:

Waterfall chart for income statement analysis

Profitability trend charts

Operating Cash Flow vs. Free Cash Flow

Free Cash Flow trend

Year and period filtering

This page helps identify how revenue is converted into operating profit, net income, and cash.

3. Balance Sheet

The Balance Sheet page provides an overview of the company's financial position.

Key metrics include:

Latest Balance Sheet Period

Total Assets

Current Liabilities

Cash & Short-Term Investments

Short-Term Debt

Inventory

Debt-to-Equity

Equity Ratio

Annualized ROE

Main visuals:

KPI cards

Balance sheet trend analysis

Debt and equity ratio analysis

ROE gauge

Year filtering

🧮 Key Financial Measures

The dashboard uses dedicated Power BI measures for financial analysis.

Income Statement

Revenue

Cost of Revenue

Gross Profit

Gross Margin %

SG&A

Operating Income

Operating Margin %

Net Income

Net Margin %

EPS (Basic)

Cash Flow

Operating Cash Flow

Free Cash Flow

Balance Sheet

Total Assets

Current Liabilities

Cash & Short-Term Investments

Short-Term Debt

Inventory

Debt-to-Equity

Equity Ratio

Annualized ROE

🏗️ Data Model

The Power BI model is organized around a financial fact table and supporting dimensions.

Main Tables

FactFinancials

DimCompany

DimLineItem

DimPeriod

DimStatement

The model separates financial transactions/measures from descriptive dimensions, allowing the report to support reusable DAX calculations and interactive filtering.

Simplified Model

                 DimCompany
                     │
                     │
DimLineItem ─── FactFinancials ─── DimPeriod
                     │
                     │
               DimStatement

This structure supports analysis by company, financial line item, reporting period, and statement category.

🔍 Interactivity

The dashboard includes interactive filtering to make financial analysis easier.

Users can filter the report by:

Year

Reporting period

Financial dimensions available in the model

Selections dynamically update the report visuals and financial measures.

🛠️ Tools & Technologies

Technology

Purpose

Microsoft Power BI

Dashboard development and visualization

DAX

Financial measures and KPI calculations

Power Query

Data preparation and transformation

Data Modeling

Relationships between facts and dimensions

Interactive Visuals

Financial trend and ratio analysis

📈 Business Questions Answered

This dashboard can help answer questions such as:

How is revenue changing over time?

Is gross profitability improving or declining?

How are operating income and net income trending?

How much cash is generated from operations?

Is free cash flow improving?

What is the company's latest asset position?

How are cash, inventory, and short-term debt changing?

What is the company's debt-to-equity position?

What percentage of the company is financed through equity?

How is annualized ROE performing?

💡 Key Analytical Areas

Revenue & Profitability

Analyze revenue growth and how effectively revenue is converted into gross profit, operating income, and net income.

Cash Generation

Compare operating cash flow and free cash flow to understand the company's ability to generate cash.

Financial Position

Evaluate assets, liabilities, debt, cash, inventory, and equity to understand the company's balance-sheet strength.

Financial Ratios

Use profitability, leverage, and equity ratios to provide additional context beyond absolute financial values.

🖼️ Dashboard Preview

Add screenshots of the report to this section after uploading them to the repository:

docs/
├── introduction.png
├── profitability-and-cash.png
└── balance-sheet.png

Example Markdown:

![Introduction Dashboard](docs/introduction.png)

![Profitability and Cash](docs/profitability-and-cash.png)

![Balance Sheet](docs/balance-sheet.png)

📂 Repository Structure

EAST-Finance-Pro/
│
├── README.md
├── EAST_Project.pbix
│
└── docs/
    ├── introduction.png
    ├── profitability-and-cash.png
    └── balance-sheet.png

Note: GitHub repositories can store the PBIX file, but the report requires Microsoft Power BI Desktop to open and interact with the dashboard.

🚀 How to Use

Clone or download this repository.

Install Microsoft Power BI Desktop.

Open EAST_Project.pbix.

Refresh the data if the original data source is available.

Navigate through the dashboard pages.

Use the available filters to explore financial performance.

📌 Project Highlights

Executive-style financial dashboard

Multi-page Power BI report

Dedicated DAX financial measures

Income statement analysis

Cash flow analysis

Balance sheet analysis

Financial ratio analysis

Interactive time-based filtering

Structured dimensional data model

Clear visualization of financial KPIs

👨‍💻 Author

Abdulrahman Mohamed

Data Science & Business Intelligence Enthusiast

⭐ If You Find This Project Useful

If this project helped you learn more about Power BI, DAX, financial analytics, or dashboard development, consider giving the repository a ⭐.
