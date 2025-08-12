# ⚓ Marine Liability Pricing & Risk Analysis Project

![Language](https://img.shields.io/badge/Language-Excel-16A085)
![Tool](https://img.shields.io/badge/Methodology-Actuarial%20Pricing%20Model-F39C12)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Insurance-red)

> An Excel-based actuarial pricing project analyzing marine liability claims to improve pricing accuracy, manage risk exposure, and support sustainable underwriting decisions.

---

## 1. Overview

This project uses Excel (PivotTables, charts, formulas) and actuarial methods to analyze marine liability claims, identify key loss trends, model severity and frequency, and calculate premiums adjusted for inflation, deductibles, and policy limits. The result is a pricing & risk assessment report with clear assumptions, methodology, and sensitivity-tested recommendations.

---

## 2. Business Objectives

### 2.1. Business Problem

Marine insurers face growing pressure from rising claims and volatile loss patterns.
This project aims to help underwriting and actuarial teams develop a more data-driven, transparent pricing process for liability coverage.

> **Key questions addressed:**
>
> * What are the historical trends in claim frequency and severity?
> * Which factors most significantly impact large vs. attritional claims?
> * How do policy limits and deductibles influence net losses?
> * What premium adjustments are needed to remain competitive while covering risk?

### 2.2. Business Impact & Insights

* Identified 10+ recurring loss drivers, including weather-related incidents and high-value collisions.
* Premium sensitivity analysis showed that a 5% rise in claim severity could increase required premium by 8–10%.
* Differentiated pricing for attritional vs. large loss segments reduced underwriting error by 15%.
* Clear documentation of assumptions improved pricing transparency for stakeholders.

---

## 3. Data Sources

The dataset was provided as part of an actuarial training project and loaded into Microsoft Excel for cleaning, transformation, and analysis. It contains marine liability claim records with detailed policy and loss attributes.

**Key Fields:**

* Claim Incurred (\$)
* Gross Claim Amount (\$)
* Policy Limits (\$)
* Deductible (\$)
* Gross & Net Inflation-Adjusted Claims
* Capped Net Adjusted Incurred Claim
* Attritional Claim Flag (< \$1M)
* Year of Loss

### 🔗 Dataset Links

- **Google Drive Download:**  
  [📁 View Dataset (Google Drive)](https://docs.google.com/spreadsheets/d/1SE93-AbIdNcZ3LbO3Izsl_vNNnc4AyUT/edit?usp=sharing&ouid=115534730882318352678&rtpof=true&sd=true)

---

## 4. Methodology & Excel Analysis

This section outlines the workflow from data preparation to premium calculation and risk reporting.

### 4.1. Data Cleaning & Preparation

- Standardized monetary values, claim flags, and date formats
- Derived missing columns using actuarial formulas:
  > - Gross Inflation Adjusted Claim = Gross Claim × Inflation Index
  > - Net Inflation Adjusted Claim = Gross Inflation Adjusted Claim – Deductible
  > - Capped Net Adjusted Incurred Claim = min(Net, Policy Limit)
- Filtered duplicates and corrected outlier values
- Ensured consistent attritional vs. large loss categorization

### 4.2. Exploratory Data Analysis (EDA)

- Created PivotTables to assess claim frequency, severity, and loss ratios by year and claim type
- Built charts to visualize trends in large losses, policy limit breaches, and deductible impact
- Segmented losses into attritional (< \$1M) vs. catastrophic claims for targeted modeling

### 4.3. Actuarial Pricing Model

- Applied experience-based rating:
  > - Pure Premium = Loss Frequency × Loss Severity
  > - Adjusted for inflation, exposure changes, and expense loadings
- Used credibility weighting to combine client-specific data with industry benchmarks
- Conducted sensitivity analysis on severity, frequency, and inflation assumptions

### 4.4. Risk Commentary & Reporting

- Documented all assumptions and methodologies in a pricing report
- Provided scenario testing (best-case, base-case, worst-case) for portfolio resilience
- Outlined potential regulatory and market impacts on pricing stability

---

## 5. Project Report

The project deliverable is a detailed Excel-based actuarial pricing & risk assessment report containing:

- Data cleaning & calculated metrics
- Premium calculations with sensitivity testing
- Written commentary on assumptions, risks, and recommendations

📄 **[View Full Project Report](https://drive.google.com/file/d/1hSsFWxDAFfA2NYXEGrgZjDSBnbMxgHri/view?usp=sharing)**

---

## 6. Final Conclusion

This project demonstrates the power of Excel as a standalone tool for actuarial pricing and risk assessment. Without the need for coding or external platforms, we developed a pricing model and comprehensive report that help marine insurers make faster, data-driven decisions in a competitive and volatile market.

**Key takeaways:**

- Segmenting attritional and catastrophic losses improves pricing accuracy and reduces underwriting error
- Inflation-adjusted claim analysis prevents underestimation of required premiums
- Sensitivity-tested pricing recommendations increase transparency and support better stakeholder decision-making

**Future Enhancements:**

- Automate inflation adjustment factors using external economic indices
- Expand datasets to include vessel-specific and route-specific risk variables
- Integrate stochastic modeling for extreme event simulation

Overall, this practical Excel-based actuarial project demonstrates strong analytical thinking and the ability to turn complex marine insurance data into actionable pricing strategies.
