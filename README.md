#  Customer 360° Banking Analytics

### Customer 360° Analytics & Next Best Product Recommendation using Python and Power BI

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-blue?logo=numpy)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

##  Project Overview

This project presents a **Customer 360° Banking Analytics solution** designed to help relationship managers understand customer profiles, financial behavior, existing banking product relationships, and potential cross-selling opportunities.

The solution combines **Python-based data generation, data analysis, feature engineering, opportunity scoring, and recommendation logic** with an interactive **Power BI dashboard**.

The project focuses on transforming customer-level banking data into actionable insights for relationship management and potential product opportunities.

> **Note:** This is an independent portfolio project using fully synthetic banking data. It is not based on real customer data or actual ICICI Bank customer records.

---

##  Business Objective

The objective is to provide relationship managers with actionable customer insights that can help them:

- Understand customer demographics and financial profiles
- Analyze customer financial behavior
- Identify high-value customers
- Analyze existing banking product penetration
- Identify potential product gaps
- Identify potential cross-selling opportunities
- Prioritize customers based on opportunity levels
- Recommend potential Next Best Products
- Support customer-centric relationship management
- Enable data-driven customer engagement

---

##  Project Workflow

```text
Synthetic Banking Dataset
          ↓
Data Validation & Cleaning
          ↓
Exploratory Data Analysis
          ↓
Customer 360° Feature Engineering
          ↓
Customer Value Analysis
          ↓
Product Penetration Analysis
          ↓
Product Gap Analysis
          ↓
Opportunity Scoring
          ↓
Next Best Product Recommendation
          ↓
Power BI Dashboard
          ↓
Business Insights
 Dataset

The project uses a synthetic dataset containing 1,000 banking customers and 23 features.

Dataset Characteristics
Records: 1,000 customers
Features: 23
Data Type: Synthetic
Domain: Banking / Customer Analytics
Purpose: Portfolio and educational analysis
Key Attributes
Category	Features
Customer Profile	Customer ID, Age, Gender, Occupation, City
Financial Profile	Monthly Income, Account Balance, Credit Score
Banking Products	Existing Loan, Credit Card, Investment, Insurance
Customer Engagement	Monthly Transactions, Digital Usage
Product Analytics	Product Count
Opportunity Analytics	Credit Card Score, Investment Score, Insurance Score, Loan Score
Recommendation	Max Opportunity Score, Next Best Product
Customer Classification	Opportunity Level, Customer Value
🐍 Python Data Analysis

Python was used to generate, validate, analyze, and transform the synthetic banking customer dataset.

Analysis Performed
Synthetic banking dataset generation
Data validation
Missing-value analysis
Duplicate detection
Descriptive statistics
Demographic analysis
Financial profile analysis
Customer behavior analysis
Product penetration analysis
Customer value classification
Product gap analysis
Product opportunity scoring
Next Best Product recommendation
Python Libraries
Python
Pandas
NumPy
Matplotlib
Scikit-learn


 Data Validation & Cleaning

The dataset was validated before performing customer analytics.

Validation steps included:
Checking dataset dimensions
Checking data types
Checking missing values
Checking duplicate customer records
Validating categorical fields
Validating numerical fields
Checking customer-level records
Preparing a clean dataset for Power BI

The final dataset contains 1,000 customer records with no missing values.

 Customer 360° Analysis

The Customer 360° approach combines multiple dimensions of customer information into a single analytical view.

Customer Dimensions Analyzed
Customer demographics
Age
Gender
Occupation
City
Monthly income
Account balance
Credit score
Existing banking products
Monthly transactions
Digital usage
Product count
Customer value
Product opportunity

This provides a consolidated view of customer relationships and potential business opportunities.

 Customer Value Analysis

Customers were classified into three broad customer-value categories:

High Value
Medium Value
Emerging

The classification uses customer financial characteristics such as:

Monthly income
Account balance

This allows relationship managers to distinguish between different customer-value segments when reviewing potential opportunities.

 Product Penetration Analysis

The project analyzes the number of banking products currently held by each customer.

Products Considered
💳 Credit Card
📈 Investment
🛡️ Insurance
🏦 Existing Loan

Product penetration analysis helps identify customers with fewer existing products who may have additional relationship opportunities.

 Product Gap Analysis

Product gaps were identified by comparing customers' existing product holdings with potential product opportunities.

The analysis evaluates whether customers currently have:

Credit Card
Investment
Insurance
Loan

A product gap does not automatically mean that the customer should receive or purchase that product.

Instead, the gap is evaluated together with customer-level financial and behavioral characteristics to identify potential opportunities.

📈 Credit Card Opportunity Analysis

Potential credit card opportunities were identified using a rule-based scoring approach considering factors such as:

Existing credit card ownership
Monthly income
Credit score
Monthly transactions

Customers meeting stronger opportunity conditions receive higher credit-card opportunity scores.

 Investment Opportunity Analysis

Potential investment opportunities were evaluated using factors such as:

Existing investment ownership
Monthly income
Account balance
Customer age

This helps identify customers who may have stronger potential for investment-related relationship opportunities based on the synthetic dataset.

 Insurance Opportunity Analysis

Potential insurance opportunities were evaluated using factors such as:

Existing insurance ownership
Monthly income
Customer age
Existing loan relationship

The resulting score is used as an analytical signal for potential insurance opportunities.

 Loan Opportunity Analysis

Potential loan opportunities were evaluated using factors such as:

Existing loan status
Monthly income
Credit score
Monthly transactions

The scoring framework helps identify customers who may represent potential loan-related opportunities.

 Opportunity Scoring

A rule-based product opportunity scoring framework was developed to prioritize potential customer-product opportunities.

Each product receives a score between 0 and 100.

Product Scores
Credit Card Score
Investment Score
Insurance Score
Loan Score

The scoring framework considers factors such as:

Monthly income
Account balance
Credit score
Existing products
Monthly transactions
Customer age
Product ownership
Customer value
Product penetration

The highest product-specific score is used to identify the customer's potential Next Best Product.
 Opportunity Level

Customers are categorized into three opportunity levels:

High
Medium
Low

The opportunity level provides a simplified way for relationship managers to prioritize customer interactions.

 Next Best Product Recommendation

A Next Best Product recommendation was generated using product-specific opportunity scores.

Potential Recommendations
 Credit Card
 Investment
 Insurance
 Loan
No Immediate Opportunity
Recommendation Logic
Customer Profile
       ↓
Existing Products
       ↓
Financial & Behavioral Signals
       ↓
Product-Specific Scores
       ↓
Highest Opportunity Score
       ↓
Next Best Product

The recommendation framework demonstrates how customer analytics can support targeted relationship management and potential cross-selling decisions.

The recommendation engine is a transparent, rule-based portfolio demonstration using synthetic data. It does not represent actual bank eligibility criteria, internal banking policies, or financial advice.

 Power BI Dashboard

The Power BI solution contains two analytical dashboard pages.

1️ Customer 360° Overview

The Customer 360° Overview provides a consolidated view of the customer base.

Key Performance Indicators
Total Customers
Average Monthly Income
Average Account Balance
Average Credit Score
Average Products per Customer
Key Visualizations
Customers by Occupation
Customers by City
Customer Value Distribution
Banking Products per Customer
Customer Financial Profile
Customer-level filtering using slicers
Dashboard Preview

2️ Product Opportunity Analysis

The Product Opportunity Analysis page focuses on identifying potential banking product opportunities.

Key Performance Indicators
Credit Card Opportunities
Investment Opportunities
Insurance Opportunities
Loan Opportunities
Key Analysis
Potential Next Best Product
Opportunity Priority
Opportunity Score Distribution
Product-level opportunity comparison
High-priority customer identification
Customer opportunity table
City, occupation, product, and opportunity filters
Dashboard Preview

 Business Insights
1. High-value customers with low product penetration

Customers with strong financial profiles but relatively few existing banking products can represent potential opportunities for deeper customer relationships.

2. Product-specific opportunities

The analysis identifies potential opportunities across:

Credit Cards
Investments
Insurance
Loans
3. Customer prioritization

Opportunity scores allow relationship managers to prioritize customers based on analytical signals rather than treating the entire customer base uniformly.

4. Customer 360° perspective

Combining demographic, financial, behavioral, and product information provides a more complete understanding of customer relationships.

5. Data-driven relationship management

The dashboard transforms customer-level data into actionable business insights that can support customer engagement and relationship-building activities.

6. Potential cross-selling opportunities

Customers with strong financial characteristics and limited product holdings can be identified as potential opportunities for deeper banking relationships.

 Banking Use Case

This project demonstrates a practical banking analytics use case relevant to Relationship Management.

A relationship manager can use the dashboard to:

Identify Customer
       ↓
Understand Financial Profile
       ↓
Review Existing Products
       ↓
Identify Potential Product Gap
       ↓
Evaluate Opportunity Score
       ↓
View Next Best Product
       ↓
Prioritize Customer Engagement

The objective is to support a customer-centric relationship management approach where potential product opportunities are evaluated using customer-level information.

 Technology Stack
Technology	Purpose
Python	Data generation and analysis
Pandas	Data manipulation and analysis
NumPy	Numerical operations
Matplotlib	Exploratory data visualization
Scikit-learn	Analytical processing
Power BI	Interactive dashboard development
DAX	Business calculations and measures
GitHub	Version control and portfolio management
 Repository Structure
customer-360-banking-analytics/
│
├── data/
│   └── customer_360_powerbi.csv
│
├── notebooks/
│   └── customer_360_analysis.ipynb
│
├── powerbi/
│   └── Bank Customer 360 Overview.pbix
│
├── screenshots/
│   ├── customer_360_overview.png
│   └── product_opportunities.png
│
└── README.md
 Key Skills Demonstrated
Data Analytics
Customer 360° Analytics
Banking Analytics
Data Cleaning
Exploratory Data Analysis
Feature Engineering
Customer Segmentation
Customer Value Analysis
Product Penetration Analysis
Product Gap Analysis
Cross-Sell Opportunity Analysis
Opportunity Scoring
Next Best Product Recommendation
Business Intelligence
Power BI
DAX
Interactive Dashboard Design
KPI Development
Business Reporting
Customer Prioritization
Business Insight Generation
Technical Skills
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Data Visualization
GitHub
 Project Outcomes

This project demonstrates the ability to:

Generate and work with synthetic banking customer data
Validate and clean structured datasets
Transform raw customer data into analytical features
Analyze financial and behavioral customer attributes
Analyze banking product penetration
Identify potential product gaps
Classify customers based on business value
Create customer-level opportunity scores
Generate Next Best Product recommendations
Build interactive Power BI dashboards
Create DAX-based business measures
Translate analytical results into actionable business insights
Present analytics in a relationship-management context
 Future Enhancements

Potential future improvements include:

Machine learning-based Next Best Product prediction
Customer Lifetime Value prediction
Churn probability integration
Predictive cross-selling models
Advanced customer segmentation using clustering
Customer propensity modeling
Real-time customer scoring
Automated Power BI data refresh
Branch-level performance analysis
Relationship manager performance tracking
Customer-level recommendation explanations
 Disclaimer

This project uses fully synthetic banking data created for educational and portfolio purposes.

It does not contain real ICICI Bank customer data, confidential information, actual customer records, or official ICICI Bank product eligibility rules.

The project is an independent portfolio project designed to demonstrate how customer analytics and business intelligence techniques can be applied to a banking relationship-management use case.

The opportunity scores and Next Best Product recommendations are rule-based analytical demonstrations and should not be interpreted as financial advice or actual banking product eligibility decisions.

 Author
Saba Sultana

M.Sc. Data Science | Data Analytics | Business Intelligence

Interested in:

Data Analytics
Business Intelligence
Banking Analytics
Customer Analytics
Power BI
Python
SQL
