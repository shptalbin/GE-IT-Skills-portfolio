# 🖥 GE-IT-Skills-portfolio
## 💭 ABOUT ME:
## Hi! I'm Shamsiyah Hayya P. Talbin
### Mananaging risks rather than avoiding them.
## Brand Identity Hex Codes
- #fdeed9
- #ffadc6
- #a98360
- #473a120
- #fdeed9

# 📊 Data Analytics and Visual Report
## Dataset Focus: Davao Region Agricultural Production Index (Mock CSV Analysis)
### 1. Data Cleaning Protocol Log 
- Raw Input Problem: The CSV file contained multiple missing row cells for the year 2023 along with mixed numerical formatting styles (e.g., metric tons vs. kilograms vs. local unit "cavan" equivalents). Date formats were inconsistent (MM/DD/YYYY vs. DD/MM/YYYY), and three provinces had overlapping municipality names causing duplicate entries.
- AI Cleaning Instruction: "Scan this dataset. Identify all null rows in the 'Yield' column and replace them with the median value for that specific crop type within the same provincial cluster. Standardize all weight units to Metric Tons (MT). Parse all date columns into YYYY-MM-DD format. Remove duplicate rows based on composite key [Crop, Municipality, Year]."
- Result: Successfully normalized 120 row inputs across three provincial clusters (Davao del Norte, Davao del Sur, Davao Oriental). Imputed 47 missing yield values. Standardized 83 mixed-unit entries. Removed 12 duplicate rows. Flagged 8 outlier entries for manual review.

### Visualizations Generated
(Embedded High-Contrast Bar Chart showing Cacao Production vs. Climate Outlier Years from 2020-2025)
| Year | Cacao Yield (MT)| Climate Event |
| -------- | -------- | -------- |
|2020      |1,200     | Normal   |
|2021      |1,350     |Mild La Niña
|2022      |2,200     |El Niño
|2023      |1,150     |Typhoon Odette
|2024      |1,400     |Recovery
|2025*     |2,100      |Projected  
### 3. Human Analytical Narrative (The 'Why' Factor)
The data chart clearly shows an abrupt 18% decline in smallholder cacao output centered in late 2023, dropping from 2,200 MT in 2022 to 1,150 MT in 2023. While the automated AI analysis summary attributed this drop solely to 'weather variability,' the human context reveals a more complex story.

This drop emphasizes the urgent need for NEDA and local LGUs to invest heavily in smart solar-powered irrigation infrastructure—but not uniformly across all provinces. The 18% decline was concentrated in Davao Oriental's coastal farms, which were disproportionately affected by Super Typhoon Odette's aftershocks. Meanwhile, Davao del Norte's protected lowland farms saw a 15% increase in yield during the same period, suggesting that geographic vulnerability and farm management practices are just as critical as weather patterns.
