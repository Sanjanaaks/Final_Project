
# README - Shark Tank India Investment Analysis

## Overview
This project analyzes investment trends, founder patterns, and investor behavior on *Shark Tank India*.
It uses cleaned and standardized data extracted from the provided `Shark Tank India.csv` file.

## Files Included
1. **Sales Investment Analysis.ipynb** — Preprocessing script for cleaning and normalizing data.
2. **clean_shark_tank.csv** — Cleaned dataset with standardized column names and numeric conversions.
3. **Shark_Tank_India_Industry_Investor_Trends_Report.pdf** — Industry-wise investor trend analysis report.
4. **Shark_Tank_India_Investor_Trends_Slides.pptx** — PowerPoint presentation summarizing insights.
5. **Charts** — Bar and trend visuals included in the report.

## Methodology
- Standardized text and numeric fields.
- Converted currency values to consistent numeric form.
- Grouped data by industry to compute total and mean deal amounts.
- Extracted investors’ names and analyzed investment frequency per domain.
- Computed founder success indicators (repeat founders, team composition).

## Key Insights
- **Top Industries**: FMCG, HealthTech, EdTech dominate in deal count and investment size.
- **Investor Trends**: Namita and Vineeta focus on health/wellness; Aman and Peyush on tech/startups.
- **Founder Trends**: Teams secure higher average deals than solo founders.
- **Equity Dynamics**: Typical negotiation gap between asked vs. offered equity.

## Tools Used
- Python: pandas, matplotlib, reportlab, python-pptx
- Dataset: Shark Tank India (user-provided)
- Outputs: Clean CSV, visual report (PDF), presentation (PPTX)

## Next Steps
- Add season-wise or episode-wise analysis.
- Create investor co-investment network visualization.
- Integrate dashboard using Plotly/Dash or Power BI.

