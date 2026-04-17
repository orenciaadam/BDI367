# U.S. Affordability Gap Analysis (BDI367)

## Data Sources & Coverage

| Source | Dataset | Coverage |
|--------|--------|---------|
| Economic Policy Institute (EPI) | Family Budget Calculator (2026) | 3,143 U.S. counties × 10 family types |
| Bureau of Labor Statistics (BLS) | Occupational Employment & Wage Statistics | 30+ occupations, state & national |

**Cost Components Modeled (EPI):**  
Housing · Food · Transportation · Healthcare · Childcare · Taxes · Other Necessities  

---

## Dataset Snapshot

- **Geographic Coverage:** Nationwide (3,143 counties)  
- **Unit of Analysis:** County × Family Type  
- **Primary Metric:**  
  **Affordability Ratio = Estimated Living Costs ÷ Median Income**

---

## Overview

This project examines affordability across the United States by comparing estimated living costs with observed income data. Using the Economic Policy Institute’s Family Budget Calculator and wage data from the Bureau of Labor Statistics, we construct an affordability ratio to evaluate how sustainable everyday expenses are relative to earnings.

Across many counties, this ratio exceeds 1.0, indicating that estimated costs are higher than median income levels. At a surface level, this suggests that a large share of households would struggle to meet basic expenses under these assumptions.

---

## Interpreting the Gap

However, this result is shaped by how the data is constructed. The EPI dataset represents a modeled estimate of what families need to spend to maintain a basic standard of living, while the BLS data reflects actual earnings in the labor market. These two perspectives do not measure the same thing, and the difference between them is central to understanding the results.

Rather than treating the affordability ratio as a direct measure of financial failure, it is more useful to interpret it as an indicator of **tension between expected costs and observed income**. In other words, it highlights where the cost of maintaining a baseline standard of living may exceed what typical wages support.

---

## What the Results Suggest

The presence of many counties with ratios above 1.0 does not necessarily imply that households are consistently overspending. Instead, it points toward a set of adaptations that are common in practice:

- Households may reduce spending below modeled “recommended” levels  
- Multiple earners within a household may offset lower individual wages  
- Debt, savings, or informal support systems may bridge short-term gaps  
- Cost structures—especially housing, transportation, and healthcare—place disproportionate pressure on budgets  

These dynamics suggest that the affordability ratio captures **financial pressure and constraint**, rather than a literal inability to function economically.

---

## Broader Implications

The analysis highlights a structural issue: the estimated cost of maintaining a basic standard of living is not always aligned with typical income levels. This misalignment raises important questions about how affordability should be defined and measured.

It also suggests that traditional indicators of economic health may not fully capture the lived experience of households, particularly in regions where essential costs have risen faster than wages. Understanding this gap is critical for interpreting both policy discussions and individual financial behavior.

---

## Repository Contents

- `EDA_367.ipynb` — data exploration and calculations  
- `data_2026.xlsx` — compiled dataset  
- `WS_img1.png`, `WS_img2.png`, `WS_img3.png` — visual findings  

---
