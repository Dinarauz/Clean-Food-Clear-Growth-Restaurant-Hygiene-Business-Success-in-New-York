# Clean Food, Clear Growth: Restaurant Hygiene & Business Success in New York - Food Service & Hospitality | Public Health Analysis
![1*Fy5s0ixzI9Duo1LbnjvctA](https://github.com/user-attachments/assets/81581bc6-293a-4832-96c7-0d92a7cf8b19)

## Executive Summary:
This project analyzes 10+ years of NYC restaurant inspection data (27,000+ establishments) to determine whether health grades predict business longevity. Using survival analysis and statistical testing, the analysis reveals that borough location and cuisine type are stronger predictors of restaurant survival than health grades alone. Manhattan restaurants score highest on inspections while certain ethnic cuisines face disproportionate violation rates.

## Business Impact:
Provides actionable insights for restaurant investors, health departments, and entrepreneurs on risk factors affecting restaurant survival beyond food safety scores.

## Business Problem:
NYC has one of the most competitive restaurant markets globally. Entrepreneurs, investors, and health officials need to understand whether health inspection performance meaningfully indicates long-term business viability.

**Key Questions:**
• Should investors prioritize Grade A restaurants?
• Do certain cuisines or locations face systemic compliance challenges?
• What factors beyond sanitation predict restaurant longevity?

## Solution & Methodology

**Dataset:**
**NYC Open Data:** (https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data)
**Analysis Code:** https://github.com/Dinarauz/Clean-Food-Clear-Growth-Restaurant-Hygiene-Business-Success-in-New-York/blob/main/Restaurant_Project.ipynb

## Technical Approach:
   • **Data Pipeline:** Python (pandas) for API extraction, cleaning, and feature engineering
   • **Statistical Analysis:** T-tests, Chi-square, ANOVA, Kaplan-Meier survival curves (lifelines library)
   • **Visualization:** Seaborn, Matplotlib, Power BI dashboards

**Skills:** Python (pandas, scipy, lifelines) | Statistical Testing | Survival Analysis | Power BI | Business Analytics

**Key Findings:**
1. **Grade Distribution:** 69% Grade A | 22% Grade B | 5% Grade C
Most restaurants meet health standards, but grade alone doesn't predict survival.
2. **Median Restaurant Lifespan:** ~2 years (720-750 days)
Statistical testing showed no significant survival advantage for Grade A vs B/C restaurants.
3. **Geographic Patterns:** Manhattan leads in inspection performance, followed by Brooklyn and Queens.
4. **Cuisine-Specific Challenges:**
   • Higher violations: Bangladeshi, African, Egyptian, Filipino cuisines
   • Best performers: American restaurants and bakeries
   • Borough-cuisine disparities: Chinese/Caribbean struggle in Manhattan; Latin American in Queens; Mexican in Staten Island
5. **Pandemic Impact:** Sharp inspection decline in 2020, strong recovery since 2021.

## Business Recommendations
**For Investors:**
• Focus on Grade A establishments in Manhattan/Brooklyn with American or bakery cuisines
• Don't rely solely on health grades—operational factors matter more

**For Health Departments:**
• Allocate resources 27% more efficiently by targeting non-A establishments
• Implement multilingual training for Bangladeshi, African, Filipino operators

**For Entrepreneurs:**
• Market gap exists for Grade A Chinese restaurants in Manhattan
• American cuisine shows strongest compliance track record across all boroughs

## Power BI Dashboard:
1. https://github.com/Dinarauz/Clean-Food-Clear-Growth-Restaurant-Hygiene-Business-Success-in-New-York/blob/main/visuals/Power%20BI%20Dashboard%201.pdf
(For a live dashboard please send me an email: https://app.powerbi.com/groups/me/reports/8ffe14c9-4175-4bdd-8dd8-ff0abf18a048/a1e10bb07522024106aa?experience=power-bi)
2. https://github.com/Dinarauz/Clean-Food-Clear-Growth-Restaurant-Hygiene-Business-Success-in-New-York/blob/main/visuals/Page%203%20-%20Restaurant%20project%20dashboard%20-%20Power%20BI.pdf
(For a live dashboard please send me email: https://app.powerbi.com/groups/me/reports/8ffe14c9-4175-4bdd-8dd8-ff0abf18a048/fee15fb8eedde614ea95?experience=power-bi)

## Impact Metrics
| Metric| Value |
| :--- | :---: | 
| Restaurants Analyzed | 27,000+ | 
| Time Period | 10+ years |
| Grade A Rate | 69% | 
| Median Lifespan | ~2 years |
| Borough Coverage | All 5 NYC boroughs | 

## Limitations & Next Steps
**Current Limitations:**
   • Survivorship bias in dataset
   • No data on rent, foot traffic, or ownership changes
   • COVID-19 inspection gap (2020-2021)

**Future Enhancements:**
   • Predictive ML model for closure risk
   • Integration with economic data (rent, income by zip code)
   • Multi-city comparison for benchmarking

**Technologies:** Python | Statistical Analysis | Survival Analysis | Power BI | Predictive Modeling
Data updated through 2025 | NYC Open Data Platform
