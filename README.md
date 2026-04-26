# Impact of Eliminating Automatic Marketplace Re-Enrollment on APTC Recipients

**Author:** Shreya Shankar  
**Date:** March 19, 2026

---

## Project Overview
This policy capstone project analyzes the projected impact of **Section 112201 of the One Big Beautiful Bill Act**, passed in July 2025. Beginning in plan year 2028, this legislation eliminates automatic re-enrollment from the health insurance exchange for Advance Premium Tax Credit (APTC) recipients. Beneficiaries will be required to actively select a plan and provide updated income, residency, and household information annually to maintain their coverage.

## Analysis Methodology
The projections in this dashboard are grounded in real-world administrative data and previous research:
* **Re-enrollment Assumptions:** Based on a natural experiment in Massachusetts, this analysis assumes a **33% reduction** in Marketplace re-enrollment due to the administrative hurdles of active selection.
* **Uninsurance Estimates:** It is further assumed that **50%** of APTC recipients who fail to re-enroll will become uninsured, a figure derived from survey evidence regarding Medicaid unwinding in Southern states.
* **Statistical Modeling:** A log-linear regression of the change in uninsurance rate on log(premium) is used to examine how subsidy dependence shapes a state's vulnerability to the policy change.

## Key Findings
* **Geographic Disparities:** The policy disproportionately impacts states with already high uninsured rates, such as **Texas, Georgia, and Florida**, widening existing gaps in healthcare access.
* **Subsidy Dependence:** There is a clear inverse relationship between current out-of-pocket costs and projected uninsurance; states where consumers pay the least (and rely most on subsidies) face the steepest increases.
* **Population Impact:** Large bubbles in the analysis for states like **Texas and Florida** indicate that the absolute number of people affected is concentrated in high-dependence, high-population states.

##  How to Interact with the Dashboard
* **Toggle Map Layers:** Use the interactive buttons to switch between **Current Rate**, **Post-Policy Rate**, and the **Projected Change** in uninsurance.
* **Hover for Details:** Hover over any state in the map or any bubble in the chart to view specific statistics, including average monthly premiums after APTC and the number of consumers projected to become uninsured.
* **Regression Analysis:** View the R² value and trend line in the **Subsidy Dependence** tab to understand the correlation between cost and coverage loss.

## Repository Contents
* `index.Rmd`: The primary source code for the interactive flexdashboard.
* `index.html`: The standalone, rendered version of the dashboard.
* `data/`: Directory containing the cleaned CMS data used for the analysis.

## Real World Impact & Importance

---

## Live Dashboard
View the live, interactive project here:  
**[PASTE YOUR GITHUB PAGES URL HERE]**