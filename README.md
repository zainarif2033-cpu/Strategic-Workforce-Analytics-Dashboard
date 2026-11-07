# Strategic Workforce Analytics Dashboard

## Executive Summary
The **Strategic Workforce Analytics Dashboard** is an end-to-end data analytics solution designed to evaluate corporate workforce dynamics, employee turnover drivers, and retention risks. Built using **MySQL Workbench** for backend data structuring and **Microsoft Power BI** for advanced interactive visualization, this dashboard provides human resources leadership and corporate executives with deep, data driven insights into employee attrition patterns across a dataset of **10,000 employees**

---

## Tech Stack & Tools
* **Database & Querying:** MySQL Workbench (Data Modeling, Schema Design, Aggregation Queries)
* **Visualization & BI:** Microsoft Power BI Desktop
* **Data Processing:** Power Query, DAX (Data Analysis Expressions)

---

## Key Performance Indicators (KPI Cards)
The top section of the dashboard highlights high level organizational metrics, giving executives an immediate snapshot of workforce health:
* **Total Employees (10,000):** Represents the entire organizational headcount tracked within the scope.
* **Active Employees (7,753):** Tracks the current active workforce (Attrition = No) currently serving the organization.
* **Total Attrition (2,247):** Measures the absolute number of employees who have exited the organization.
* **Attrition Rate (22.47%):** The overarching organizational turnover rate, quantifying the proportion of departures relative to total staff.
* **Average Age (40):** Evaluates the demographic baseline age profile across the workforce.

---

## Interactive Filters & Slicers
To enable dynamic cross filtering and multi dimensional analysis, the top control bar features key filters alongside a custom **Reset Button**.
* **Job Role Filter:** Isolates specific professional functions (like Software Engineer, Data Scientist, HR, Business Analyst).
* **Job Level Filter:** Filters the analysis across hierarchical organizational grades.
* **Gender Filter:** Facilitates demographic specific turnover tracking (Male and Female).
* **Reset Button:** Instantly clears all active slicer states to restore the default global view.

---

## Workforce Rating & Demographic Distribution Cards
The upper middle section features structured horizontal micro bar charts and category grids evaluating employee behavioral metrics among departed staff.
* **Job Level Distribution:** Evaluates attrition breakdown across hierarchical corporate tiers (Levels 1 to 8).
* **Work-Life Balance Score:** Measures turnover distribution against reported work life balance ratings (Scale 1 to 5).
* **Job Satisfaction Score:** Analyzes how reported job satisfaction levels correlate with employee resignations.
* **Job Environment Rating:** Assesses the impact of workplace environment satisfaction on departures.
* **Job Involvement Score:** Evaluates employee engagement levels prior to exiting.
* **Attrition Marital Status Breakdown:** Compares turnover distribution across marital segments (**Divorced: 723**, **Married: 767**, **Single: 757**).

---

## Core Visualizations & Analytical Breakdown

### 1. Departmental & Travel Turnover Analysis
* **Attrition by Department (Donut Chart):** Breaks down employee exits across major business units, highlighting hotspots such as **Cyber Security (503)**, **Software Development (462)**, **Data Science (442)**, **IT Services (430)**, and **Network Administration (410)**.
* **Attrition due to Travel (Donut Chart):** Investigates travel frequency behavior among departing employees, categorizing exits into **Travel Rarely (1,182)**, **Travel Frequently (690)**, and **No Travel (375)**.

### 2. Experience, Education & Role Tables
* **Attrition by Education (Horizontal Bar Chart):** Analyzes turnover distribution based on academic credentials, showing high concentrations in **Graduation (702)** and **Degree (686)** levels compared to Master's, PhD, and Below College tiers.
* **Attrition by Job Role (Matrix Table):** Details precise exit volumes across functional designations such as **Consultant (208)**, **Director (199)**, **QA Analyst (199)**, **IT (198)**, **Business Analyst (184)**, **Developer (181)**, **Help Desk (181)**, **HR (181)**, and **Support (174)**.

### 3. Advanced Behavioral & Compensation Trends
* **Attrition by Distance From Home (Area Line Chart):** Evaluates commute distance impact on turnover, tracking exit counts across kilometer/mile gradients up to 30 units.
* **Attrition by Salary Hike Percentage Groups (Column Chart):** Analyzes annual percentage salary increments received by departed employees, grouped from (0 to 10) up to (91 to 100), highlighting compensation stagnation patterns.
* **Attrition by Years in Current Role (Heatmap Matrix Table):** Evaluates tenure stability within current job assignments, identifying critical resignation peaks at **5 years (235 exits)** and **4 years (227 exits)**.

---

## Key Business Insights & Strategic Recommendations
* **KPIs & Filters:** Tracks headcount, active staff, attrition volume, and demographic rates with dynamic cross filtering.
* **Tenure & Career Stagnation:** Attrition peaks heavily at **4 to 5 years of tenure**, signaling a critical need for career growth frameworks.
* **Departmental Vulnerabilities:** High demand units like **Cyber Security (503 exits)** and **Software Development (462 exits)** suffer the heaviest turnover.
* **Travel & Workload Impact:** Employees traveling frequently or rarely form the bulk of exits, highlighting travel burnout.
* **Strategic Recommendation:** Implement performance linked incentives, tech specific compensation benchmarking, and structured internal mobility.
