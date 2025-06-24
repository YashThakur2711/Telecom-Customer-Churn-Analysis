# Telecom-Customer-Churn-Analysis
📉 Telecom Churn Dashboard

An interactive Power BI dashboard designed to analyze telecom customer churn—highlighting key trends by tenure, service type, payment method, and contract length .



## Short Description / Purpose

This dashboard provides a visual, data-driven tool to explore why customers churn. It helps uncover early and long-term churn risk, service and payment drivers, and financial impacts—supporting targeted retention strategies.

---

## Tech Stack

- **Power BI Desktop** – Dashboard & report development  
- **Power Query** – Data extraction, transformation, and Condition Column  
- **DAX (Data Analysis Expressions)** – Custom measurements, churn rate, Churn Count.    
- **File Format** – `.pbix` for development; `.xlsx` / `.csv` for source data

---

## Data Source

- **Source files**: Kaggle.com 
- **Tables**:  
  - Customers ( Gender,Dependant,Partner,Senior Seticens)  
  - Contracts (length, internet, phone, protection )  
  - Billing (monthly charges, total charges)  
- **Period covered**: Tenure in Months and Year

---

## Features / Highlights

- **🔍 Business Problem**  
  High customer churn (~26.5%) is threatening revenue growth and long-term profitability.

- **🎯 Dashboard Goal**  
  Provide interactive insights around Customer churn drivers to guide business growth.

- **📊 Key Visuals Walkthrough**  
  - **KPI Cards**: Total churn count,customers,average tenure, churn rate, Charges (Total & Monthly),Percentage wise services. 
  - **Tenure Comparision** (Bar Chart): High churn in `<1 yr` groups  
  - **Internet Service Distribution** (Donut Chart): Fiber users show more churn  
  - **Security & Protection Analysis**: Compare churn counts by add-on options  
  - **Payment Method Analysis**: High churn among electronic check users  
  - **Charges Over Tenure**: Highlights long-term value before churn
  - **Monthly And Yearly charges**: Line Chart shoes charges over time period.
  - **Filter** : Slicer use for filter the visual as churn risk,contract type, tenure in months and multiple lines.

- **💡 Business Impact & Insights**  
  - Identify stages (onboarding, loyalty milestone) with highest churn risk  
  - Segment interventions by service type and payment method  
  - Estimate financial impact to prioritize churn reduction investments

---

