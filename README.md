# Responsible-AI-Readiness-in-Africahttps://gi
An interactive Power BI dashboard analysing responsible AI readiness across 39 African countries using data from the Global Index on Responsible AI (GIRAI) 2026.

![Responsible AI Readiness Dasboard](https://github.com/Techsis-22/Responsible-AI-Readiness-in-Africa/blob/main/Screenshot%20(60).png?raw=true)
![](https://github.com/Techsis-22/Responsible-AI-Readiness-in-Africa/blob/main/Screenshot%20(61).png?raw=true)
![](https://github.com/Techsis-22/Responsible-AI-Readiness-in-Africa/blob/main/Screenshot%20(62).png?raw=true)
![](https://github.com/Techsis-22/Responsible-AI-Readiness-in-Africa/blob/main/Screenshot%20(63).png?raw=true)
![](https://github.com/Techsis-22/Responsible-AI-Readiness-in-Africa/blob/main/Screenshot%20(64).png?raw=true)


### DSN AI Bootcamp 2026 Hackathon | Winning Team | Team Lead

The project investigates how African countries perform across five responsible AI dimensions, examines the relationship between enabling conditions and AI governance, identifies critical gaps in inclusion and accountability, and translates the findings into actionable recommendations for policymakers and other stakeholders.

**Project:** Responsible AI Readiness in Africa  
**Tool:** Microsoft Power BI  
**Data Source:** Global Index on Responsible AI (GIRAI) 2026  
**Team Size:** 4 members  
**Team Name:** Debuggers
**My Role:** Team Lead and Data Analyst  
**Competition:** DSN AI Bootcamp 2026 Hackathon  
**Outcome:** Winning Team

---


# 1. Project Overview

Artificial Intelligence is increasingly influencing public services, economic development, business operations, and decision-making around the world. However, the benefits of AI depend not only on technological advancement but also on the policies, institutions, safeguards, and accountability mechanisms that guide its development and use.

Responsible AI requires countries to consider issues such as inclusion, diversity, ethics, sustainability, labour protections, digital skills, public-sector readiness, cybersecurity, transparency, and public accountability.

Across Africa, countries have different levels of readiness to develop, govern, and deploy AI responsibly. Understanding these differences is important for identifying existing strengths, uncovering gaps, and determining where interventions may be most beneficial.

This project uses data from the **Global Index on Responsible AI (GIRAI) 2026** to investigate responsible AI readiness across 39 African countries.

Using Microsoft Power BI, our team developed an interactive dashboard that transforms country-level scores and indicators into meaningful visual insights.

The dashboard enables users to:

- Compare responsible AI readiness across African countries.
- Identify the highest- and lowest-scoring countries.
- Examine differences across five responsible AI dimensions.
- Compare performance across five African regions.
- Investigate AI policy, civil society engagement, and enabling conditions.
- Identify indicators associated with the largest readiness gaps.
- Explore individual country profiles.
- Translate analytical findings into recommendations for policy and capacity development.

The project was designed to go beyond presenting charts. Its purpose was to tell a data-driven story about responsible AI readiness in Africa and make the findings accessible to decision-makers, researchers, students, and other interested audiences.

## 2. Problem Statement

As AI adoption expands, African countries need appropriate governance frameworks, institutional capacity, inclusive policies, and accountability mechanisms to support responsible AI development and deployment.

However, responsible AI readiness cannot be adequately understood by looking at a single overall score.

A country might have relatively strong digital or institutional foundations but weak AI-specific policies. Another country might perform relatively well in cybersecurity while struggling with inclusion, labour protections, or transparency.

These differences raise important questions:

- How does Africa perform overall in responsible AI readiness?
- Which countries lead the rankings, and which countries face the greatest gaps?
- Which responsible AI dimensions are strongest and weakest?
- How does performance vary across African regions?
- Do stronger enabling conditions correspond with stronger AI policy?
- Which governance and accountability indicators require the greatest attention?
- How can the findings inform more targeted and effective interventions?

Without a structured analytical approach, these patterns can be difficult to identify and communicate from a large dataset.

This project addresses the problem by developing an interactive Power BI dashboard that brings together overall scores, country rankings, regional comparisons, dimension-level analysis, governance indicators, and actionable recommendations.

The ultimate objective is to support a clearer understanding of responsible AI readiness and help stakeholders identify areas that merit further investigation and targeted action.

---

# 3. Project Objectives

The project was guided by the following objectives.

### 3.1 Assess Continental Readiness

Establish the average GIRAI score for the African countries included in the dataset and use it as a reference point for country and regional comparisons.

### 3.2 Compare Country Performance

Identify countries with relatively high and low GIRAI scores and investigate the differences between them.

### 3.3 Analyse Responsible AI Dimensions

Examine the five dimensions of responsible AI readiness to identify areas of relative strength and weakness.

### 3.4 Investigate Regional Differences

Compare North Africa, West Africa, Southern Africa, East Africa, and Central Africa to understand how readiness varies geographically.

### 3.5 Examine AI Governance

Investigate the relationship between enabling conditions, AI policy, and civil society organisation engagement.

### 3.6 Identify Critical Indicators

Highlight indicators with particularly low scores, including public disclosure of government algorithmic systems, labour protections, gender equality, and civil society engagement.

### 3.7 Develop Evidence-Based Recommendations

Translate the analytical findings into recommendations that could inform policy development, accountability, inclusion, capacity building, and regional collaboration.

### 3.8 Build an Interactive Analytical Tool

Develop a Power BI dashboard that allows users to explore the data through filters, visual comparisons, country profiles, and supporting insights.

---

# 4. Dataset Overview

## Data Source

The analysis uses the **Global Index on Responsible AI (GIRAI) 2026**.

The source report indicates that the underlying global dataset covers 135 countries, including 39 African countries assessed in this project.

The dataset contains country-level scores across responsible AI dimensions, governance pillars, and individual indicators.

### Scope of Analysis

| Item | Description |
|---|---|
| Source | Global Index on Responsible AI |
| Dataset edition | GIRAI 2026 |
| Global dataset coverage | 135 countries |
| African countries analysed | 39 |
| Responsible AI dimensions | 5 |
| Governance pillars | 3 |
| Primary analytical tool | Microsoft Power BI |
| Data preparation | Power Query |
| Analytical calculations | DAX |
| Country matching | ISO3 country codes |

The findings in this dashboard apply to the 39 African countries represented in the dataset. They should not be interpreted as a complete assessment of every African country.

## 4.1 The Five Responsible AI Dimensions

The analysis examines five dimensions.

| Dimension | Description |
|---|---|
| Inclusion and Diversity | Examines inclusion-related considerations, including gender equality and children's rights. |
| Ethics and Sustainability | Examines ethical and sustainability-related aspects of responsible AI. |
| Labour and Skills | Covers labour protections, skills, and related readiness indicators. |
| AI in Public Service | Examines responsible AI considerations in public-sector services and government activities. |
| Trust and Safety | Covers trust, safety, cybersecurity, consumer protection, and related safeguards. |

These dimensions provide a more detailed picture of readiness than an overall score alone.

## 4.2 The Three Governance Pillars

The dashboard also examines three governance pillars.

**AI Policy**

Represents the policy-related component of responsible AI readiness.

**Civil Society Organisation (CSO) Engagement**

Represents the civil society engagement component of the index.

**Enabling Conditions**

Represents the enabling-conditions component of the index.

Comparing these pillars helps investigate whether the conditions supporting AI readiness are accompanied by strong AI policy and civil society engagement.

**Data interpretation note:** GIRAI scores are index scores. They should not automatically be interpreted as percentages or as direct measurements of the percentage of a country that is ready for AI.

---

# 5. Tools and Technologies

## Microsoft Power BI

Power BI was used to develop the interactive dashboard and communicate the findings through multiple visualisation techniques.

The dashboard combines headline KPIs, country rankings, a geographical map, regional comparisons, scatter plots, heatmaps, and indicator-level charts.

## Power Query

Power Query was used to clean and prepare the dataset for analysis.

The project report describes the data preparation process as including the integration of country-level data using ISO3 country codes.

## DAX

Data Analysis Expressions (DAX) was used to build analytical measures supporting the dashboard.

The report identifies measures for:

- African average scores.
- Score variance.
- Country rankings.
- Strongest and weakest dimensions.
- Indicator-level views.

## GitHub

GitHub provides a platform for documenting the project, presenting the dashboard screenshots, explaining the analytical findings, and sharing the project files where appropriate.

The README is intended to make the project understandable to recruiters, analysts, researchers, and other readers without requiring them to open Power BI first.

---

# 6. Project Methodology

The project followed a structured analytical process, moving from data preparation to visual analysis and recommendations.

## Step 1: Define the Analytical Questions

The first step was to establish the questions the dashboard needed to answer.

These included understanding continental readiness, comparing countries, identifying the weakest dimensions, investigating governance gaps, and translating findings into recommendations.

Defining these questions helped give each dashboard page a clear analytical purpose.

## Step 2: Prepare the Dataset

The project used Power Query to clean and prepare the GIRAI dataset.

The report identifies ISO3 country codes as the basis for joining country-level information in a star-style data model.

Using a consistent country identifier helps match records across tables without relying exclusively on variations in country names.

The exact transformation steps and treatment of missing values should be documented from the Power Query implementation if a fully reproducible technical record is required.

## Step 3: Build the Data Model

The report describes a star-style model that joins the relevant data using ISO3 country codes.

This modelling approach supports the integration of country information and the measures required for the dashboard.

The model provides a foundation for filtering, comparing, and analysing country-level scores.

## Step 4: Develop DAX Measures

DAX measures were created to support the main analytical questions.

These measures include calculations for the African average, score variance, country rankings, strongest and weakest dimensions, and indicator views.

The measures enable the dashboard to display summary results and support interactive analysis.

## Step 5: Develop the Visualisations

Different chart types were selected based on the analytical purpose of each visual.

- KPI cards summarise key metrics.
- Horizontal bar charts compare countries, regions, dimensions, and indicators.
- A filled map provides geographical context.
- A scatter plot explores the relationship between enabling conditions and AI policy.
- A heatmap reveals patterns across countries and dimensions.
- Tables provide more detailed country-level comparisons.

## Step 6: Build the Interactive Dashboard

The report includes slicers for country, income group, and subregion.

Navigation buttons guide users between the five pages, while cross-filtering, drill-through, and hover tooltips support exploration.

## Step 7: Validate the Findings

The project report states that the headline figures were validated against the official GIRAI Africa page.

This step helps ensure that the dashboard's key metrics align with the referenced source.

## Step 8: Develop Insights and Recommendations

The final stage involved translating the numerical findings into a structured set of insights and proposed interventions.

Rather than leaving the reader to interpret the charts independently, the dashboard explicitly connects the findings to potential actions.

---

# 7. Dashboard Overview

The Power BI report contains five analytical pages.

| Page | Primary Purpose |
|---|---|
| Overview | Present continental readiness, country rankings, and regional comparisons. |
| Dimensions | Investigate strengths and gaps across the five responsible AI dimensions. |
| Governance | Examine enabling conditions, AI policy, civil society engagement, and weak indicators. |
| Country Profile | Explore an individual country's score, dimensions, governance pillars, and indicators. |
| Insights & Recommendations | Summarise the findings and present potential interventions. |

Together, these pages guide users from a high-level overview to deeper investigation and practical recommendations.

---

# 8. Detailed Dashboard Analysis

## 8.1 Page One: Overview

**Analytical question:** What does responsible AI readiness look like across Africa?

The Overview page provides a summary of continental performance, highlights the highest- and lowest-scoring countries, and compares regional averages.

### A. Overall African GIRAI Score

**Score: 21.79**

The dashboard reports an average GIRAI score of 21.79 for the African countries included in the analysis.

The accompanying report compares this with an average of 40.4 for countries elsewhere.

This provides context for understanding Africa's overall position within the index.

The score also serves as a reference point for interpreting the country rankings and regional comparisons.

**Insight:** The continental average masks considerable variation between countries. Some score substantially above the African average, while others fall well below it.

### B. Highest-Performing Countries

The dashboard identifies Nigeria as the highest-scoring country in the African comparison.

| Rank | Country | GIRAI Score |
|---:|---|---:|
| 1 | Nigeria | 45.93 |
| 2 | Egypt | 41.26 |
| 3 | Kenya | 39.53 |
| 4 | Ghana | 38.43 |
| 5 | Benin | 37.01 |

Nigeria's score of 45.93 is substantially above the African average of 21.79.

These countries provide useful starting points for investigating areas of relative strength and identifying opportunities for peer learning.

However, the overall rankings alone do not establish which specific policies or institutions explain each country's performance.

### C. Lowest-Performing Countries

| Country | GIRAI Score |
|---|---:|
| South Sudan | 4.04 |
| Chad | 6.51 |
| Burundi | 8.70 |
| Congo | 8.73 |
| Central African Republic | 9.44 |

These countries occupy the bottom five positions in the reported African ranking.

Their scores are substantially below the continental average.

**Insight:** The difference between the highest- and lowest-scoring countries highlights the uneven distribution of reported responsible AI readiness across Africa.

**Recommendation:** Investigate the specific dimensions and indicators contributing to low scores before designing targeted capacity-building programmes.

### D. Country Ranking Chart

**Visualisation:** Horizontal bar chart

The country ranking chart orders the 39 African countries by GIRAI score.

An average reference line helps users compare each country with the African benchmark.

The chart supports:

- Identification of the highest- and lowest-scoring countries.
- Comparison between countries with similar scores.
- Identification of countries above and below the continental average.
- Recognition of the scale of differences across the ranking.

A horizontal bar chart is appropriate because it accommodates long country names and makes ranking comparisons easy to interpret.

### E. GIRAI Score by Country

**Visualisation:** Filled map

The map displays the geographical distribution of GIRAI scores across African countries.

It provides a spatial perspective on responsible AI readiness and helps users recognise where relatively higher and lower scores occur.

The map complements the country ranking by communicating geographical patterns rather than relying solely on a numerical list.

### F. Regional Performance

**Visualisation:** Horizontal bar chart

The regional comparison reveals the following averages.

| Region | GIRAI Score |
|---|---:|
| North Africa | 27.07 |
| West Africa | 24.76 |
| Southern Africa | 23.74 |
| East Africa | 21.00 |
| Central Africa | 9.88 |

North Africa records the highest regional score at 27.07, while Central Africa records the lowest at 9.88.

The gap between these regions is substantial.

East Africa's score of 21.00 is close to the continental average of 21.79.

**Insight:** Responsible AI readiness varies not only between individual countries but also across the regional groupings used in the dataset.

**Recommendation:** Use the regional results to identify areas for further investigation and collaboration, while examining individual countries to avoid overlooking differences within each region.

---

## 8.2 Page Two: Dimension Analysis

**Analytical question:** Which aspects of responsible AI readiness show the greatest gaps?

The Dimensions page investigates the five responsible AI dimensions and identifies where performance is relatively strong or weak.

### A. Dimension Scores Across Africa

| Dimension | Score | Relative Position |
|---|---:|---|
| Trust and Safety | 26.36 | Highest |
| Ethics and Sustainability | 23.38 | Second highest |
| Labour and Skills | 23.30 | Third highest |
| AI in Public Service | 19.73 | Fourth |
| Inclusion and Diversity | 16.68 | Lowest |

Trust and Safety records the highest dimension score at 26.36.

Inclusion and Diversity records the lowest at 16.68.

The difference between the two scores is 9.68 points.

**Insight:** The results indicate uneven performance across the dimensions of responsible AI readiness.

A relatively strong score in one dimension does not necessarily imply equally strong performance in other areas.

### B. Strongest and Weakest Dimensions by Country

**Visualisation:** Table

The dashboard compares each country's overall score with its strongest and weakest dimensions.

This helps users move beyond country rankings and examine the internal composition of each country's result.

For example, Nigeria's strongest dimension is Trust and Safety, at 63.45, while its weakest is AI in Public Service, at 23.65.

This illustrates why country-level analysis should consider more than an overall score.

A country may perform relatively well in one area while having a substantial gap in another.

**Analytical value:** The table supports country-specific diagnosis and helps identify where improvement efforts may be most useful.

### C. Dimension Heatmap by Country

**Visualisation:** Heatmap

The heatmap compares country scores across the five responsible AI dimensions.

Each row represents a country, while each column represents a dimension.

Colour intensity communicates differences in scores, allowing users to identify:

- Countries with relatively high scores across several dimensions.
- Countries with substantial differences between their strongest and weakest dimensions.
- Dimensions where low scores recur across multiple countries.
- Country-specific patterns that may be hidden by overall rankings.

The heatmap is particularly useful because it presents several numerical variables across many countries in one compact visual.

**Insight:** Country performance is multidimensional. An overall ranking does not provide sufficient detail to understand every country's strengths and weaknesses.

**Recommendation:** Use the heatmap to identify recurring gaps and develop more targeted follow-up analysis.

---

## 8.3 Page Three: Governance and Enabling Conditions

**Analytical question:** What does the data reveal about AI policy, enabling conditions, and accountability?

The Governance page examines three governance pillars and investigates the relationship between enabling conditions and AI policy.

### A. Enabling Conditions Versus AI Policy

**Visualisation:** Scatter plot

The scatter plot compares enabling-conditions scores with AI policy scores.

Each point represents a country, with colours distinguishing the regional groups used in the dashboard.

The chart helps identify countries with relatively strong enabling conditions but weaker AI policy scores, as well as countries that perform relatively well on both measures.

**Insight:** Stronger enabling conditions do not automatically translate into stronger AI policy.

The pattern suggests that countries may have favourable institutional or digital foundations while still facing challenges in establishing or implementing AI-specific governance arrangements.

The scatter plot supports exploratory analysis but does not establish a causal relationship.

### B. Governance Pillars

**Visualisation:** Clustered column chart

| Governance Pillar | Score |
|---|---:|
| Enabling Conditions | 42.48 |
| AI Policy | 13.69 |
| Civil Society Organisation Engagement | 9.31 |

Enabling Conditions records 42.48, considerably higher than AI Policy at 13.69 and Civil Society Organisation Engagement at 9.31.

**Insight:** The difference between the governance pillars suggests that enabling foundations and AI-specific governance do not perform at the same level in the continental summary.

This raises questions about how existing institutional strengths can be translated into policy development, implementation, and public accountability.

### C. Enabling Conditions and AI Policy Correlation

The report identifies a correlation of approximately **0.34** between enabling conditions and AI policy across the 39 countries.

This indicates a positive but limited linear association.

Countries with higher enabling-conditions scores tend to have higher AI policy scores to some extent, but the relationship is far from perfect.

The finding suggests that other factors may also be associated with AI policy performance.

**Important:** Correlation does not establish causation.

### D. Ten Weakest Indicators in Africa

**Visualisation:** Horizontal bar chart

The dashboard highlights the following low-scoring indicators.

| Indicator | Score |
|---|---:|
| Civil Society Engagement in Ethics and Sustainability | 9.86 |
| Gender Equality | 8.64 |
| Children's Rights | 8.54 |
| Civil Society Engagement in Inclusion and Diversity | 7.69 |
| Environmental Impact | 7.12 |
| AI-facilitated Misinformation and Violence | 6.59 |
| Public Procurement | 6.48 |
| Civil Society Engagement in Trust and Safety | 5.19 |
| Labour Protections | 2.84 |
| Public Disclosure of Government Algorithmic Systems | 0.00 |

Public Disclosure of Government Algorithmic Systems records 0.00, while Labour Protections records 2.84.

Several civil society engagement indicators also appear among the ten weakest indicators.

**Insight:** Transparency, labour protections, inclusion, and civil society participation emerge as important areas for further investigation.

A score of zero should be interpreted according to the source index's methodology. It should not automatically be interpreted as proof that no relevant activity exists in every country.

### E. Digital Skills, Equality, Cybersecurity and Rule of Law

The dashboard compares four indicators.

| Indicator | Score |
|---|---:|
| Cybersecurity | 64.82 |
| Skills and Literacy | 41.38 |
| Rule of Law | 34.06 |
| Gender Equality | 8.64 |

Cybersecurity records the highest score among the four indicators, while Gender Equality records the lowest.

**Insight:** The findings illustrate that technical safeguards and inclusion-related indicators can perform very differently.

This reinforces the importance of examining responsible AI through multiple dimensions rather than relying on a single measure of technical readiness.

---

## 8.4 Page Four: Country Profile

**Analytical question:** How can users investigate responsible AI readiness at the country level?

The Country Profile page supports drill-through analysis of an individual country.

It brings together overall scores, ranking information, dimension comparisons, governance pillars, and the highest- and lowest-scoring indicators.

### A. Selected GIRAI Score

Displays the overall score associated with the selected country.

This provides a starting point for investigating the country's performance.

### B. Africa Rank

Displays the selected country's position in the African ranking when a valid country selection is made.

The measure supports comparison between a country and the other African countries included in the dataset.

### C. Global Rank

Provides a place for the selected country's global ranking where supported by the source data and the implemented ranking measure.

A global ranking should only be presented when the underlying data and calculation support it.

### D. Variance Versus Africa Average

Compares the selected country's score with the continental benchmark.

This helps users identify whether the country is above or below the African average.

For reliable comparisons, the African benchmark should remain fixed when the country selection changes.

### E. Dimension Scores Versus Africa Average

Compares the selected country's scores across the five dimensions with the corresponding African averages.

This supports a more detailed investigation of the areas where a country performs relatively well or poorly.

### F. Governance Pillars

Displays the selected country's AI Policy, Civil Society Engagement, and Enabling Conditions scores.

This allows users to investigate whether the relationship observed in the continental summary is also visible at the country level.

### G. Top Five Indicators

For the all-country selection shown in the dashboard, the top five indicators are:

| Indicator | Score |
|---|---:|
| Consumer Protection | 76.13 |
| Cybersecurity | 64.82 |
| Civil Society Accountability | 57.22 |
| Data Protection and Privacy | 56.50 |
| Public Service Delivery | 55.68 |

These results identify areas of relative strength in the aggregate indicator profile.

### H. Bottom Five Indicators

For the all-country selection, the bottom five indicators are:

| Indicator | Score |
|---|---:|
| AI-facilitated Misinformation and Violence | 6.59 |
| Public Procurement | 6.48 |
| Civil Society Engagement in Trust and Safety | 5.19 |
| Labour Protections | 2.84 |
| Public Disclosure of Government Algorithmic Systems | 0.00 |

The bottom-five chart reinforces the importance of transparency, labour protections, and civil society engagement in the wider analysis.

**Analytical value of the Country Profile page:** It allows users to investigate individual countries rather than relying exclusively on continent-wide averages and rankings.

---

## 8.5 Page Five: Insights and Recommendations

**Analytical question:** What actions could stakeholders consider based on the findings?

The final page translates the analysis into five major findings and corresponding recommendations.

### Insight 1: Africa Trails the World, with Wide Gaps Within the Continent

Africa's average GIRAI score is 21.79, compared with 40.4 for countries elsewhere.

Only 18 of the 39 African countries included in the analysis score above the African average.

**Recommendation:** Prioritise capacity support for lower-scoring countries while exploring opportunities for peer learning with higher-scoring countries.

### Insight 2: Inclusion Is the Weakest Dimension

Inclusion and Diversity records 16.68, the lowest of the five responsible AI dimensions.

Gender Equality and Children's Rights also appear among the ten weakest indicators.

**Recommendation:** Investigate how inclusion safeguards, gender considerations, children's rights, and inclusive datasets can be incorporated into national AI strategies and public-sector guidance.

### Insight 3: Strong Foundations Do Not Guarantee Strong AI Governance

Enabling Conditions records 42.48, while AI Policy records 13.69.

The correlation between the two measures is approximately 0.34.

The report also identifies 15 countries with above-average enabling conditions but below-average AI policy scores.

**Recommendation:** Investigate opportunities to strengthen AI-specific legislation, national strategies, regulator mandates, and implementation capacity in these countries.

### Insight 4: Accountability and Transparency Are Major Gaps

Civil Society Engagement averages 9.31.

Public Disclosure of Government Algorithmic Systems scores 0.00 in every country according to the report, while Public Procurement scores 6.48 and Labour Protections scores 2.84.

**Recommendation:** Explore mechanisms to strengthen civil society participation, public disclosure, transparency, and AI procurement standards.

### Insight 5: Central Africa Needs a Regional Approach

Central Africa records an average score of 9.88, compared with 27.07 for North Africa.

The report identifies common weaknesses involving algorithmic transparency, labour protections, and civil society engagement.

**Recommendation:** Consider regional collaboration, shared policy resources, pooled technical support, and peer-learning initiatives while accounting for individual countries' needs.

---

# 9. Key Insights and Findings

The analysis produced several headline findings.

## Finding 1: Responsible AI Readiness Varies Substantially Across Africa

The African average is 21.79, but country scores range from Nigeria's 45.93 to South Sudan's 4.04.

This highlights the importance of examining both the continental picture and individual country performance.

## Finding 2: Inclusion and Diversity Is the Weakest Dimension

Inclusion and Diversity scores 16.68, compared with 26.36 for Trust and Safety.

This indicates that the dimensions do not perform uniformly and that inclusion-related issues deserve closer investigation.

## Finding 3: Central Africa Records the Lowest Regional Average

Central Africa scores 9.88, substantially below North Africa's 27.07.

Regional comparisons can help identify where additional analysis and collaboration may be valuable.

## Finding 4: Enabling Conditions Outperform AI Policy and Civil Society Engagement

Enabling Conditions scores 42.48, compared with 13.69 for AI Policy and 9.31 for Civil Society Engagement.

The difference suggests that favourable foundations are not necessarily accompanied by equally strong performance in other governance pillars.

## Finding 5: Transparency and Accountability Indicators Are Particularly Weak

Public Disclosure of Government Algorithmic Systems scores 0.00, while Labour Protections scores 2.84.

Several civil society engagement indicators also appear among the weakest results.

These findings highlight areas for further investigation into transparency, participation, and accountability.

## Finding 6: Technical and Inclusion-Related Indicators Show Different Patterns

Cybersecurity scores 64.82, while Gender Equality scores 8.64.

This contrast demonstrates why responsible AI readiness should be assessed through a combination of technical, social, ethical, and governance-related indicators.

## Finding 7: The Data Supports More Targeted Investigation

The differences between countries, regions, dimensions, and governance indicators suggest that a uniform intervention may not address every gap.

Country-level and indicator-level analysis can help stakeholders determine where further assessment and support may be most useful.

---

# 10. Recommendations

Based on the findings, the dashboard proposes five priority areas for further investigation and action.

| Priority | Area of Focus | Proposed Action | Supporting Finding |
|---|---|---|---|
| 1 | AI-specific governance | Investigate AI legislation, strategies, and regulatory mandates in countries with strong enabling conditions but weak AI policy. | Enabling Conditions: 42.48; AI Policy: 13.69. |
| 2 | Transparency and accountability | Explore public disclosure mechanisms, civil society oversight, and AI procurement standards. | CSO Engagement: 9.31; Public Disclosure: 0.00. |
| 3 | Inclusion and public services | Investigate gender equality, children's rights, and safeguards for public-sector AI. | Inclusion and Diversity: 16.68; AI in Public Service: 19.73. |
| 4 | Regional capacity building | Explore peer learning and shared technical support for lower-scoring countries and regions. | Central Africa: 9.88. |
| 5 | Existing strengths | Investigate how stronger cybersecurity and data protection practices can support broader responsible AI governance. | Cybersecurity: 64.82; Data Protection and Privacy: 56.50. |

These recommendations are proposed responses to the observed patterns. The dashboard does not independently establish that implementing any specific intervention will cause a particular improvement in GIRAI scores.

---

# 11. Interactive Features

The dashboard was designed to allow users to investigate the data rather than view a fixed report.

### Country Slicer

Allows users to select a country and explore the associated score, dimensions, governance pillars, and indicators.

### Income Group Slicer

Allows users to filter the dataset by income group where the relevant classification is available.

This supports descriptive comparisons between groups of countries.

### Subregion Slicer

Allows users to focus on particular geographical groupings and examine regional patterns.

### Navigation Buttons

The dashboard contains navigation buttons for:

- Overview
- Dimensions
- Governance
- Country Profile
- Insights and Recommendations

These buttons provide a structured route through the analysis.

### Cross-Filtering

Cross-filtering allows selections in supported visuals to influence other visuals on the page.

This helps users investigate relationships between country performance, dimensions, and other measures.

### Drill-Through

The Country Profile page supports drill-through analysis, allowing users to move from a broader view to a more detailed country-level investigation.

### Hover Tooltips

Tooltips provide additional information when users hover over supported visuals.

This allows users to explore details without overcrowding the main dashboard with labels.

### Clear Filters

The Clear Filters button allows users to reset their selections and return to a broader view of the data.

Together, these features make the dashboard more flexible and support exploratory analysis.

---

# 12. Data Analysis and DAX

DAX was used to support the dashboard's analytical calculations.

The project report identifies the following types of measures.

### African Average

Provides the benchmark used to compare country scores against the African average.

### Score Variance

Measures the difference between a selected score and a reference value.

The interpretation depends on the exact DAX formula and filter context used in the report.

### Country Ranking

Determines a country's position in the relevant ranking based on its GIRAI score.

### Strongest and Weakest Dimensions

Identifies the highest- and lowest-scoring dimensions for the relevant country or selection.

### Indicator Views

Supports the presentation and comparison of indicator-level scores, including the highest- and lowest-scoring indicators.

### Correlation Analysis

The report examines the relationship between enabling conditions and AI policy.

It reports a correlation of approximately 0.34 between these variables.

The result indicates a positive but limited linear association and should not be interpreted as proof of causation.

**Technical documentation note:** The measures listed above reflect the project report. For full reproducibility, the exact DAX expressions, table names, column names, and filter-handling logic should be documented from the Power BI model itself rather than reconstructed from the dashboard screenshots.

---

# 13. Business and Policy Value

Although this project focuses on responsible AI readiness rather than a commercial sales dataset, the analytical principles are relevant to decision-making in government, business, research, and development organisations.

### Evidence-Based Prioritisation

The country rankings and indicator-level comparisons help identify areas that may warrant further investigation.

### Performance Benchmarking

The African average provides a reference point for comparing countries and regions.

### Gap Analysis

The dimension analysis and heatmap reveal differences that may be hidden by aggregate scores.

### Governance Assessment

The comparison of enabling conditions, AI policy, and civil society engagement helps frame questions about institutional readiness and accountability.

### Clear Communication

The combination of visualisations and written recommendations makes the results more accessible to non-technical audiences.

### Strategic Planning

The findings can inform discussions about possible policy priorities, regional collaboration, and capacity-building initiatives.

The dashboard should be treated as a decision-support resource rather than a substitute for detailed country-level research or policy evaluation.

---

# 14. Challenges and Lessons Learned

## Moving Beyond Attractive Charts

A visually appealing dashboard is not necessarily an effective analytical tool.

Each visualisation needs to answer a clear question and help the audience understand something meaningful about the data.

This project reinforced the importance of selecting chart types based on the analytical purpose rather than appearance alone.

## Working with Multiple Dimensions

An overall score provides a useful summary, but it can conceal substantial differences between individual dimensions.

The heatmap, dimension comparison, and country profile demonstrate the value of investigating the components of an aggregate score.

## Translating Findings into Recommendations

Identifying a low score is only the beginning of an analytical investigation.

A useful dashboard should also explain why the finding matters and what additional actions could be considered.

The Insights and Recommendations page was designed to connect the data with practical questions about policy and governance.

## Interpreting Relationships Carefully

The governance analysis demonstrates the importance of distinguishing correlation from causation.

A positive relationship between two variables does not establish that one causes the other.

## Designing for Different Audiences

The dashboard combines headline KPIs for quick interpretation with more detailed visualisations for users who want to investigate the data.

This balance helps make the findings accessible without removing the detail needed for deeper analysis.

## Collaboration and Leadership

Working as a four-member team reinforced the importance of communication, coordination, and maintaining a shared analytical objective.

The project also demonstrated the value of connecting individual contributions to a coherent final deliverable.

---

# 15. My Role as Team Lead

I participated in the DSN AI Bootcamp 2026 hackathon as the team lead of a four-member team.

Our project focused on analysing responsible AI readiness across Africa and communicating the findings through an interactive Power BI dashboard.

As team lead, I contributed to coordinating the team's efforts and maintaining a clear connection between the analytical questions, dashboard design, and final recommendations.

The project required more than creating individual visualisations. It involved bringing different analytical components together into a report that communicates a consistent story.

My experience on this project strengthened my understanding of how data analytics can support the investigation of complex policy questions.

It also reinforced the importance of communicating insights in a way that is understandable to technical and non-technical audiences.

**Key professional skills demonstrated through the project include:**

- Data analysis and interpretation.
- Power BI dashboard development.
- Data visualisation and analytical storytelling.
- KPI and performance comparison.
- Exploratory analysis of relationships between variables.
- Evidence-based recommendation development.
- Team coordination and collaboration.
- Analytical problem-solving.
- Communication of technical findings.

## Project Achievement

**Our four-member team won the DSN AI Bootcamp 2026 challenge.**

This achievement was particularly meaningful because it represented the combined effort of the team to investigate a complex issue, analyse the data, and communicate the findings through an interactive dashboard.

It was also an opportunity to apply my Power BI skills to a topic with implications for governance, inclusion, accountability, and Africa's technological development.

---

# 16. Project Limitations

Several limitations should be considered when interpreting the findings.

### Coverage of African Countries

The analysis covers 39 African countries, not every country on the continent.

The results should therefore be interpreted within the scope of the available dataset.

### Index-Based Measurements

GIRAI scores summarise the indicators and methodology used by the source index.

They should not automatically be interpreted as percentages or complete measures of every aspect of responsible AI readiness.

### Correlation Does Not Establish Causation

The correlation between enabling conditions and AI policy is approximately 0.34.

This indicates an association but does not prove a causal relationship.

### Regional Groupings

The regional comparisons use the subregion classifications supplied with the dataset.

Different geographical classification systems could produce different groupings.

### Global Ranking Availability

The report identifies Nigeria as ranking 38th globally.

Global ranking claims for other countries should be verified against the source data before publication.

### Recommendations Require Further Evaluation

The recommendations are based on patterns observed in the dashboard.

Assessing whether a particular intervention would improve responsible AI readiness would require additional research, implementation evidence, and evaluation.

---

# 17. Future Improvements

The project could be extended in several ways.

### 17.1 Add Historical Comparisons

If comparable GIRAI data from multiple years become available, a time-series analysis could show how responsible AI readiness changes over time.

### 17.2 Improve Country Profile Benchmarks

Ensure that continental averages remain fixed when a country is selected, so users can compare the selected country against a consistent reference point.

### 17.3 Expand Regional Analysis

Investigate differences between individual countries within each region rather than relying exclusively on regional averages.

### 17.4 Strengthen the Data Documentation

Document the source fields, transformations, data types, missing-value treatment, model relationships, and DAX measures.

This would improve reproducibility and make the project easier for other analysts to understand.

### 17.5 Add More Detailed Governance Analysis

Investigate how governance indicators vary across countries and income groups.

This could help identify recurring patterns and support more targeted exploratory analysis.

### 17.6 Improve Dashboard Usability

Provide clear messages when a country-specific ranking is unavailable, ensure that all visuals respond appropriately to filters, and distinguish aggregate results from individual country results.

---

# 18. How to Explore the Project

You can explore the project through the dashboard files provided by the team.

### Option 1: View the Dashboard PDF

The PDF provides a static overview of the dashboard pages and the main analytical findings.

### Option 2: Open the Power BI File

The `.pbix` file provides access to the Power BI report for interactive exploration, subject to the file's compatibility and any required supporting resources.

To explore the report:

1. Download the Power BI project file.
2. Open it using Microsoft Power BI Desktop.
3. Navigate between the dashboard pages.
4. Use the country, income group, and subregion slicers.
5. Explore the country rankings and dimension comparisons.
6. Investigate the governance indicators.
7. Review the Insights and Recommendations page.

Some report features may depend on the supporting map file or other resources included in the project folder.

---

# 19. Project Files

The team documentation identifies a Google Drive folder containing the Power BI file, PDF export, and Africa map file.

**Project folder:**

[Open the Responsible AI Readiness in Africa project files](https://drive.google.com/drive/folders/1URTP41KNMK5raZRkVkEABp0nOTY8A-Rh?usp=drive_link)

---

# 20. Conclusion

The Responsible AI Readiness in Africa Dashboard demonstrates how data analytics can help investigate complex questions about governance, inclusion, accountability, and technological readiness.

Using the Global Index on Responsible AI 2026, the project examines 39 African countries across five responsible AI dimensions and three governance pillars.

The findings reveal considerable differences between countries and regions.

Trust and Safety records the highest dimension score, while Inclusion and Diversity records the lowest. Enabling Conditions scores considerably higher than AI Policy and Civil Society Engagement. Central Africa records the lowest regional average, while Nigeria leads the African country ranking presented in the dashboard.

These findings demonstrate why responsible AI readiness should not be assessed through a single aggregate score.

Country rankings provide an overview, but dimension analysis, governance indicators, regional comparisons, and country profiles provide a deeper understanding of the gaps that may require attention.

The dashboard also demonstrates the importance of connecting analysis with communication. Through its combination of interactive visualisations and recommendations, it provides a structured way to explore the findings and consider possible responses.

For me, this project was an opportunity to apply Power BI to a meaningful analytical question, collaborate with a team, and contribute to a project that connects data with real-world issues.

**Winning the DSN AI Bootcamp 2026 challenge as the leader of a four-member team made the experience especially rewarding.**

It reinforced my belief that data analytics is not just about creating charts. It is about asking the right questions, interpreting evidence carefully, identifying meaningful patterns, and communicating findings in a way that supports better decisions.

---

# 21. Acknowledgements

I would like to thank **Data Science Nigeria (DSN)** for providing the learning environment and challenge through the DSN AI Bootcamp 2026.

I also appreciate my three teammates for their collaboration and contributions to our winning project.

Finally, I acknowledge the Global Index on Responsible AI as the source of the data used in this analysis.

### Project Summary

| Category | Details |
|---|---|
| Project | Responsible AI Readiness in Africa |
| Data Source | Global Index on Responsible AI (GIRAI) 2026 |
| Countries Analysed | 39 African countries |
| Tool | Microsoft Power BI |
| Data Preparation | Power Query |
| Calculations | DAX |
| Dashboard Pages | 5 |
| Team Size | 4 members |
| My Role | Team Lead and Data Analyst |
| Competition | DSN AI Bootcamp 2026 Hackathon |
| Outcome | Winning Team |


**Thank you for exploring my project!**
