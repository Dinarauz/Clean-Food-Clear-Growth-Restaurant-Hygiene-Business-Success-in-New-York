# Clean Food, Clear Growth: Restaurant Hygiene & Business Success in New York - Food Service & Hospitality | Public Health Analysis
![1*Fy5s0ixzI9Duo1LbnjvctA](https://github.com/user-attachments/assets/81581bc6-293a-4832-96c7-0d92a7cf8b19)

## Executive Summary:
This project analyzes 10+ years of NYC restaurant inspection data (27,000+ establishments) to determine whether health grades predict business longevity. Using survival analysis and statistical testing, the analysis reveals that borough location and cuisine type are stronger predictors of restaurant survival than health grades alone. Manhattan restaurants score highest on inspections while certain ethnic cuisines face disproportionate violation rates.

## Business Impact:
Provides actionable insights for restaurant investors, health departments, and entrepreneurs on risk factors affecting restaurant survival beyond food safety scores.

## Business Problem:
NYC has one of the most competitive restaurant markets globally. Entrepreneurs, investors, and health officials need to understand whether health inspection performance meaningfully indicates long-term business viability.

**Stakeholder Questions:**
• Should investors prioritize Grade A restaurants when evaluating acquisition opportunities?
• Do certain cuisines or locations face systemic compliance challenges?
• How can health departments allocate resources to support struggling restaurant segments?
• What factors beyond sanitation predict restaurant longevity?

**Why This Matters:** Understanding the relationship between health compliance and business survival helps reduce investment risk, improve public health outcomes, and support sustainable restaurant operations in NYC's $5 billion+ restaurant industry.

## Solution & Methodology

**Dataset:**
NYC Open Data: (https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data)
• 27,000+ restaurants tracked across 5 boroughs
• 10+ years of inspection records (2015-2025)
• Health grades, violation codes, inspection scores, and operational status

**Key Questions:**
1. Do restaurants with Grade A stay active longer than Grades B or C?
2. Are some cuisines more prone to poor grades or shorter lifespans?
3. How does restaurant lifespan differ across boroughs?
4. Can health grades or inspection scores predict early restaurant closures?

**Tools Used:**
1. Python: pandas, seaborn, matplotlib, lifelines
2. Statistical testing: T-test, Chi-square, ANOVA
3. Survival Analysis: Kaplan - Meier curves
4. Visualization: Box/violin plots, heatmaps, line charts
5. Power BI: Dashboard
   
**Key Findings:**
1. Approximately over 69% of restaurants earned a Grade A, while 22% received a B and just 5% a C. That tells me the majority of places citywide are following health and safety guidelines.
2. The median lifespan for NYC restaurants sits between 720–750 days — about two years. Interestingly, A-graded spots stick around longer than lower-graded or ungraded places like those marked “N.” However, during my hypothesis testing violin plot showed that assymption of Grade A restaurant surive significantly better is not supported. In fact data showed that Grade B and C follow comparable patterns which suggesting that final inspection grade may not be reliable predictor of business longevity. 
3. When looking at average inspection scores by borough, things were mostly consistent. That said, Manhattan being at top out the others, followed closely by Brooklyn and Queens.
4. Inspections were steadily increasing from 2015 until a sharp dip in 2020 (pandemic). Since 2021, activity has picked back up, which is a good sign for the restaurant industry overall.
5. I looked into whether certain cuisines get flagged more often — and it turns out Bangladeshi, African, Egyptian, and Filipino restaurants had higher average inspection scores (aka more violations).
6. American and Chinese cuisines make up the largest share of restaurants, but Chinese spots were more likely to get lower grades compared to American ones.
7. American restaurants and bakeries had the highest rate of A grades, while Caribbean, Latin American, Chinese, and Mexican spots saw more B’s and C’s.
8. Some cuisines fared worse in certain boroughs. For example, Chinese and Caribbean restaurants struggled more in Manhattan; Latin American spots had issues in Queens. Staten Island inspections were tougher on Mexican food, and in the Bronx, Caribbean, Latin American, and Japanese cuisines saw more violations. Brooklyn’s trends mirrored that too, especially for Caribbean and Latin American spots. Whether it’s heavier inspection or actual compliance issues, the borough and cuisine type clearly play a role.
   
**Power BI Dashboard:**
1. https://github.com/Dinarauz/Clean-Food-Clear-Growth-Restaurant-Hygiene-Business-Success-in-New-York/blob/main/visuals/Power%20BI%20Dashboard%201.pdf
(For a live dashboard please send me an email: https://app.powerbi.com/groups/me/reports/8ffe14c9-4175-4bdd-8dd8-ff0abf18a048/a1e10bb07522024106aa?experience=power-bi)
2. https://github.com/Dinarauz/Clean-Food-Clear-Growth-Restaurant-Hygiene-Business-Success-in-New-York/blob/main/visuals/Page%203%20-%20Restaurant%20project%20dashboard%20-%20Power%20BI.pdf
(For a live dashboard please send me email: https://app.powerbi.com/groups/me/reports/8ffe14c9-4175-4bdd-8dd8-ff0abf18a048/fee15fb8eedde614ea95?experience=power-bi)



