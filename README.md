# Electricity-Consumption-And-Tarriff-Analysis(Hands-On)
Excel data analysis project analyzing customer electricity usage, billing calculations, and tariff distribution across multiple states.

## Project Overview
This project analyzes household and commercial power consumption records to evaluate tariff distributions, verify billing correctness, and identify customers on high-cost pricing plans.

## Dataset Structure
* **ElectricityUsage:** Complete records of 200 customers covering consumption (kWh), billing amounts, unit costs, and verification status.
* **Customers on most expensive Tariff:** Filtered subset highlighting customers on maximum pricing tiers.
* **TariffRates:** Reference lookup table for plan-specific pricing.

## Key Insights
* **Tariff Distribution:** Evaluated usage across multiple pricing tiers (e.g., R1, R2, C1, MD) to identify customer volume per plan.
* **Billing Audit:** Cross-checked computed billing amounts (`New_bill`) against recorded totals to ensure pricing calculation accuracy.
* **High-Cost Exposure:** Isolated customer segments subjected to the most expensive unit rates to review cost distribution.

## Tools & Skills Used
* **Microsoft Excel:** Data cleaning, conditional formatting, data validation, and multi-sheet relational lookups (`XLOOKUP`/`VLOOKUP`).
* **Data Analysis:** Aggregations, conditional filtering, and structural validation.

## Conclusion
This project demonstrates how structured Excel workflows and relational lookups can effectively audit billing accuracy and segment customer consumption across multiple utility tariff tiers. By isolating high-cost tariff users and validating unit rate calculations, utility providers can ensure transparent billing, minimize revenue leakage, and better understand consumption distribution across states.
