# Injectable-Anesthesia-Market-Analysis
Medicare CCLF claims analysis of the injectable  anesthesia market using Python. Includes data pipeline,  HCP segmentation, territory analysis, and a 3-phase  commercial strategy across 4 competing pharmaceutical brands.

# BIA 810 — Injectable Anesthesia Market Analysis
### Neural Numb-ers | Stevens Institute of Technology | Spring 2026

---

## Project Overview

This project analyzes Medicare CCLF institutional claims data 
from 2016 to 2018 across four injectable anesthesia products 
to identify competitive market share erosion and develop a 
data-driven three-phase commercial strategy.

The team operated as a Commercial Analytics team at a 
pharmaceutical company tasked with answering four Key Business 
Questions for sales and marketing leadership.

---

## The Business Problem

A company launched a new variant brand (Product 2 / Midazolam) 
to absorb the declining sales of its market leader 
(Product 1 / Ketorolac). Instead of capturing that share, 
a competitor (Product 3 / Fentanyl) nearly doubled its 
market share in three years while the new brand barely moved.

---

## Market Basket

| HCPCS Code | Brand | Generic | Role |
|---|---|---|---|
| J1885 | Ketotrom | Ketorolac | Our Old Brand |
| J2250 | Midoride | Midazolam | Our New Brand |
| J3010 | Fentirate | Fentanyl | Main Competitor |
| J2704 | Profativ | Propofol | Alt Competitor |

---

## Key Findings

- Fentanyl claims share grew from 14.3% to 28.8% (2016 to 2018)
- Midazolam claims share declined from 10.0% to 5.4%
- 84 lapsed writers identified who wrote Midazolam in 2017 
  and zero in 2018
- 428 shared writers increasingly favoring Fentanyl
- 273 unconverted specialists never tried Midazolam despite 
  being a clinical fit
- Top 5 at-risk territories: New York NY, LA-San Diego CA, 
  Phoenix AZ, St Louis MO, Minneapolis MN

---

## Three-Phase Commercial Strategy

**Phase 1 — HCP Retention**
Reactivate 84 lapsed writers using existing reps with zero 
new budget. Projected recovery of 60 incremental claims 
within 90 days.

**Phase 2 — Reclaim Shared Writers**
Develop clinical differentiation messaging for 428 doctors 
writing both products but favoring Fentanyl. Projected 
recovery of 73 additional claims within 90 to 120 days.

**Phase 3 — Specialist Targeting**
Convert 35 unconverted specialists in the first wave across 
Anesthesiology, Gastroenterology, and Orthopedics. Projected 
52 new annual claims within 12 months.

**Total projected impact: 185 incremental annual claims**
**Total estimated investment: $140K to $270K**

---

## Key Business Questions Answered

**KBQ 1** — Market dynamics and competitive landscape analysis

**KBQ 2** — Key market drivers including HCP specialty, 
diagnosis specialty, patient age distribution, and 
new vs continuing writer trends

**KBQ 3** — Three-phase strategy to stop market share erosion

**KBQ 4** — Data exploration opportunities including DDD, 
Xponent, NPA, CRM call data, NPP response data, 
and MMIT formulary data

---

## Repository Structure

| File | Description |
|---|---|
| Jeel_Patel_Data_Engineering.ipynb | Full data pipeline, cleaning, joins, and aggregations |
| Jeel_Patel_Data_Engineering.html | Rendered notebook viewable without Python |
| final_project_810.ipynb | KBQ analysis, charts, and business insights |
| final_project_810.html | Rendered notebook viewable without Python |
| BIA_810_Final_Project_PPT.pdf | Final presentation deck |

---

## Data Sources

Medicare CCLF institutional claims data provided for 
academic use at Stevens Institute of Technology.

Raw data files are not included in this repository 
due to data privacy requirements.

Reference datasets used:
- HCP Demographics (2,000 providers)
- Patient Demographics (4,508 patients)
- ZIP to Territory Mapping (41,683 ZIP codes, 22 territories)
- Diagnosis Code Mapping (ICD-10 to specialty)
- Procedure Code Mapping (CPT codes to surgical categories)

---

## Tools and Technologies

- Python, Pandas, NumPy, Matplotlib, Seaborn
- PyMuPDF for PDF claims data parsing
- Google Colab
- Medicare CCLF Institutional Claims Data

---

## Team

| Name | Role |
|---|---|
| Jeel Patel | Data Engineering and Pipeline |
| Preetham Deepak Kumar | Data Support and KBQ Analysis |
| Frederick Blake | Visualizations and Phase 2 Strategy |
| Sherwin Christian | Executive Summary, Phase 1 and Phase 3 |
| Poojan Mehta | Python Code and Conclusion |

**Course:** BIA 810D — Health Care Data and Analytics
**Professor:** Sanjiv Koshal
**Institution:** Stevens Institute of Technology
**Semester:** Spring 2026
