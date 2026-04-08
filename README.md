# Healthcare-Provider-Analysis-Project
## Project Overview
This project focuses on analyzing a healthcare provider dataset to uncover operational efficiency, patient behavior, and revenue performance. The dataset contains approximately 5,000 patient visit records, including details on patients, providers, departments, diagnoses, procedures, and financial metrics.
The primary objective is to transform raw healthcare data into actionable insights that support data-driven decision-making, particularly in improving service delivery, optimizing resource allocation, and increasing revenue.
All financial values in this analysis are represented in British Pounds (£).
## Project Description

The dataset represents a hospital or multi-specialty healthcare system, where each record corresponds to a patient visit.

#### Key Components:

Patient demographics (age, gender, city)

Visit records (date, department, provider)

Clinical data (diagnosis and procedures)

#### Financial data:

Insurance coverage (£)

Room charges (£)

#### Business Problem:

##### Healthcare providers often struggle with:

Low patient retention

Inefficient provider utilization

Revenue leakage from uninsured patients

Poor visibility into high-performing departments.

This project addresses these issues through exploratory data analysis and visualization. 
## Tools Used

### Power BI

##### Used for:

Data modeling (relationships between tables)

Creating dashboards and KPIs

Visual storytelling

Power Query (within Power BI)

Data cleaning

Handling missing values

Transforming datasets

### DAX (Data Analysis Expressions)

##### Used to calculate:

Total Revenue (£)

Average Revenue per Visit

Visits per Provider

Departmental performance metrics

 ## Exploratory Data Analysis (EDA)
 #### Patient Analysis
 
Total Patients: ~4,973

Total Visits: ~5,000

##### Observation:

 Almost a 1:1 ratio → very low repeat visits

#### Visit Trends

~439 unique visit dates

Average ≈ 11–12 visits/day

Some days show extreme spikes

##### Interpretation:
Demand is inconsistent → indicates need for flexible staffing

 #### Financial Distribution (£)
 
Average Insurance Coverage: ~£456

Room Charges: Very low on average

##### Observation:

Large number of visits with £0 room charges

#### Provider Analysis

Only 5 providers handling all visits

##### Insight:

Potential workload imbalance or resource constraint

#### Department Analysis

Uneven distribution of visits across departments

##### Insight:

Some departments dominate patient traffic

## Key Insights

### Low Patient Retention

Most patients visit only once.

##### Implication:

The hospital is not effectively retaining patients for follow-ups or long-term care.

### Outpatient-Dominated Revenue Model

#### Minimal room charges indicate:

Fewer admissions

More outpatient services

##### Implication:

Revenue is driven mainly by consultations and procedures, not inpatient care.

### High Dependence on Insurance (£)

Insurance coverage is the primary revenue contributor.

#### Risk:

Changes in insurance policies could significantly impact income.

### Provider Capacity Risk

A small number of providers manage all visits.

##### Implication:

Risk of burnout

Reduced service quality

Longer patient wait times

### Demand Volatility

Visit spikes on certain days.

##### Implication:

Poor demand forecasting and staffing inefficiencies.

 ### Presence of Uninsured Patients

Some visits lack insurance coverage.

##### Implication:

Potential revenue loss or bad debt.

## Recommendations

### Improve Patient Retention

Introduce follow-up scheduling systems

Implement loyalty or care programs

Use automated reminders

### Expand Outpatient Services

#### Since outpatient care drives activity:

Invest in faster consultation systems

Introduce telemedicine services

### Optimize Provider Allocation

Balance workload across providers

Hire additional staff if necessary

Introduce shift-based scheduling

### Diversify Revenue Streams

#### Reduce reliance on insurance:

Offer private healthcare packages

Subscription-based health plans

### Implement Demand Forecasting

Use historical data to predict peak days

Adjust staffing dynamically

### Reduce Revenue Leakage

Improve billing systems

Introduce payment plans for uninsured patients

## Conclusion

This analysis reveals that the healthcare provider operates a high-volume, outpatient-focused model with strong dependence on insurance-based revenue.

#### While the organization demonstrates consistent patient inflow, it faces critical challenges in:

Patient retention

Resource optimization

Revenue diversification

By leveraging Power BI insights and implementing the recommended strategies, the healthcare provider can significantly improve operational efficiency, financial stability, and patient experience.
