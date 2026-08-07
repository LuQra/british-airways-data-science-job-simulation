# ✈️ Task 1: Modeling Lounge Eligibility at Heathrow Terminal 3

## Lookup Table Preview

![Lookup Table](BA_Lounge_Eligibility_Lookup_Table.png)

## Project Overview

This project was completed as part of the **British Airways Data Science Job Simulation** on Forage.

The objective was to develop a scalable lookup table that estimates passenger lounge eligibility across different flight categories at Heathrow Terminal 3. The model enables British Airways to forecast lounge demand for future flight schedules without requiring detailed aircraft or passenger-level information.

By grouping flights into meaningful categories and calculating lounge eligibility percentages, the solution provides a practical approach to support airport planning and resource allocation.

---

## Business Problem

Lounge access is an important part of the premium travel experience offered by British Airways. As flight schedules, destinations, and fleet strategies continue to evolve, accurately forecasting lounge demand becomes increasingly challenging.

Without a flexible forecasting approach, British Airways may experience:

- Overcrowded lounges during peak periods
- Underutilized lounge capacity
- Inefficient staffing and resource allocation
- Difficulty planning future lounge investments

The Airport Planning team required a simple yet scalable solution capable of estimating lounge demand using broad flight characteristics rather than detailed operational data.

---

## Objective

The objective of this project was to create a lookup table that estimates the percentage of passengers eligible for each lounge tier based on flight characteristics.

Specifically, the project aimed to:

- Categorize flights into meaningful operational groups
- Estimate lounge eligibility percentages for each group
- Build an Excel lookup table for future demand forecasting
- Provide business justification for each grouping

---

## Methodology

The lookup model was developed using historical flight information and operational assumptions.

Flights were grouped using:

- **Flight Haul**
  - Short-haul
  - Long-haul

- **Time of Day**
  - Morning
  - Afternoon
  - Evening

These groupings were used to calculate estimated eligibility percentages across three lounge access tiers.

The completed lookup table includes:

- Flight grouping
- Example destinations
- Tier 1 eligibility
- Tier 2 eligibility
- Tier 3 eligibility
- Business interpretation

---

## Deliverables

- Excel-based Lounge Eligibility Lookup Table
- Estimated lounge eligibility percentages by flight category
- Business interpretation for each flight grouping
- Scalable forecasting framework for future schedules

---

## Key Insights

The analysis identified noticeable differences in lounge eligibility across flight categories.

Some key observations include:

- Short-haul evening flights showed the highest proportion of Tier 3 lounge eligibility.
- Long-haul morning flights generally exhibited higher premium lounge eligibility than other long-haul time periods.
- Different flight groupings demonstrated distinct lounge demand patterns, highlighting the importance of considering operational characteristics when forecasting lounge capacity.

These insights can support more effective planning of lounge space, staffing requirements, and customer experience initiatives.

---

## Business Value

The lookup table provides British Airways with a flexible forecasting tool that can be applied to future schedules without relying on exact passenger manifests or aircraft configurations.

The model helps the Airport Planning team:

- Forecast future lounge demand
- Support capacity planning
- Improve staffing decisions
- Allocate lounge resources efficiently
- Inform long-term infrastructure investment decisions

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Lookup Tables
- Data Analysis

---

## Repository Contents

```
Task_1_Lounge_Eligibility/
│
├── Lounge_Eligibility_Lookup_Table.xlsx
└── README.md
```

---

## Skills Demonstrated

- Business Analytics
- Data Analysis
- Data Aggregation
- Excel Modeling
- Forecasting
- Critical Thinking
- Business Communication

---

## Acknowledgements

This project was completed as part of the **British Airways Data Science Job Simulation** hosted on **Forage**.
