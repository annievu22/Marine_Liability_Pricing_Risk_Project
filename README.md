# ⚓ Marine Liability Pricing & Risk Analysis Project

![Language](https://img.shields.io/badge/Language-Excel-16A085)
![Tool](https://img.shields.io/badge/Methodology-Actuarial%20Pricing%20Model-F39C12)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Insurance-red)

> An Excel-based actuarial pricing model and interactive dashboard assessing Marine Liability insurance risk, applying experience-based rating, inflation adjustments, and large loss loadings to produce competitive yet sustainable premiums.

---

## 1. Overview

This project uses Microsoft Excel to analyze six years of historical marine liability claims data (2018–2023) and produce an actuarially sound premium for the upcoming policy year. The work combines risk assessment, experience-based rating, large loss handling, and sensitivity testing, supported by a dynamic dashboard for stakeholder communication.

---

## 2. Business Objectives

### 2.1. Business Problem

Marine insurers face volatility in claims cost due to high-severity but low-frequency events, such as environmental pollution or major collisions. Pricing needs to balance competitiveness with financial stability, accounting for trends, inflation, and rare catastrophic losses.

> **Key questions addressed:**
>
> * What are the trends in claims frequency and severity over time?
> * Which claim types and locations contribute the most to losses?
> * How should large loss events be incorporated into the premium?
> * What is the impact of changes in claim severity on overall pricing?

### 2.2. Business Impact & Insights

* Environmental Pollution emerges as the costliest risk, both in frequency and severity.
* The Atlantic Ocean has the highest severity due to a $5M pollution loss.
* Large loss loadings reduce year-to-year premium volatility.
* Sensitivity analysis reveals significant premium changes with small shifts in severity.

---

## 3. Data Sources

The dataset was provided as part of an actuarial pricing simulation project and loaded into Microsoft Excel for cleaning, calculation, and visualization. It includes historical Marine Liability claims for multiple insured vessels, covering claim amounts, deductibles, limits, and exposure data (gross tonnage).

**Key Fields:**

* Claim Incurred (\$)
* Gross Claim Amount (\$)
* Policy Limits (\$)
* Deductible (\$)
* Gross & Net Inflation-Adjusted Claims
* Capped Net Adjusted Incurred Claim
* Attritional Claim Flag (< \$1M)
* Year of Loss
* Claim Type (Collision, Cargo Liability, Damage to Other Vessels, Environmental Pollution, Injury to Third Parties)
* Claim Status (Closed, Open, Litigation)

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
- Included commentary on claim drivers, exposure patterns, and loss concentration risks

---

## 5. Excel Dashboard Design

The Excel dashboard allows underwriters and actuaries to explore claims patterns interactively by year, claim type, and location, supporting transparent communication with clients.

🔗 **[View Full Dashboard in Excel](https://project.novypro.com/ud876F)**

### Dashboard Snapshot

![Marine Liability Dashboard](https://github.com/annievu22/Marine_Liability_Pricing_Risk_Project/blob/main/Marine%20Liability%20Project%20-%20Dashboard.jpeg)

---

### Walkthrough of Key Visuals:
* **KPI Cards (Top Left):** 
Total Claims, Total Loss, Average Severity, Top Claim Type, and Top Loss Location.

* **Total Loss by Year (Bar Chart):** 
Tracks yearly loss patterns and highlights volatility due to large losses.

* **Loss Share by Claim Type (Pie Chart):** 
Shows proportional loss contribution from each claim category.

* **Loss Share by Location (Donut Chart):** 
Visualizes geographical loss concentration, with the Atlantic Ocean as the leading risk area.

* **Total Claims Over Time (Line Chart):** 
Displays claim volume trends over the six-year period.

* **Average Severity by Claim Type (Bar Chart):** 
Highlights costliest claim categories, guiding underwriting focus.

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
