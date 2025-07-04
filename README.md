Palmoria_HR_Analysis_Capstone_Project

## My Palmoria HR Data Analysis  

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Analysis And Insights](#analysis-and-insights)
- [Key Strategies and Recommendations](#key-strategies-and-recommendations)
- [Business Task and Dashboard Component](#business-task-and-dashboard-component)
- [Overall Conclusion](#overall-conclusion)

##  Project Overview
This project focuses on identifying and addressing gender-related inequalities within Palmoria Group, a Nigerian manufacturing company operating across three regions. The primary goal is to uncover disparities in gender distribution, performance evaluation, and salary structure using HR data analysis.
By examining employee data through Power BI, the project aims to: Provide the management with evidence-based insights on gender representation, highlight areas with potential gender pay gaps, assess compliance with new wage regulations, and support strategic decision-making around HR policy reform, diversity and inclusion initiatives, and compensation fairness.
Ultimately, the analysis supports Palmoria’s broader goal of transforming into a more equitable and globally competitive organization, ready for regional and international expansion.


---

## Objectives
- Understand gender distribution across departments and regions
- Analyze performance ratings by gender
- Identify if a gender pay gap exists and locate where it's most critical
- Evaluate compliance with the newly introduced $90,000 minimum wage law
- Allocate bonus payments based on employee performance ratings

---

##  Tools Used
- **Microsoft Power BI** BI [(http://www.microsoft.com/en-us/download)]
  (for data cleaning, visualization, and analysis) 
- **DAX** and **Power Query** (for calculated fields and logic)
- **Excel** (preprocessing and supporting bonus rule data)

---

##  Exploratory Data Analysis
- Cleaned null departments and inactive employees
- Assigned "Undisclosed" to missing gender entries
- Created salary bands in intervals of $10,000
- Merged datasets for bonus allocation based on performance

---

## Analysis And Insights:
   Data Visualization:
 - The analysis results were visualized using PowerBI.
 - Slicers were implemented to provide interactivity and enhance the dashboard's usability. Overall, the analysis and visualization process facilitated a thorough examination of the data, enabling the extraction of valuable insights and presenting them in an interactive and visually appealing manner.

  These are as a result of our analysis:
  
### 1. Gender Distribution
- Males dominate the workforce across all three regions.
- Some departments had no female representation, indicating bias in hiring or retention.

### 2. Ratings vs Gender
- Males received slightly higher average ratings.
- Fewer women were found in the top performance category, which affects bonuses and promotions.

### 3. Gender Pay Gap
- Significant pay gaps found in departments like Engineering and Sales.
- South and West regions showed more disparity than the North.

### 4. Minimum Wage Compliance
- Not all employees earned the required minimum of $90,000.
- Most below-compliance salaries were in the South region.
- Created a salary band chart showing how many employees fall within each $10,000 range.

### 5. Bonus Allocation
- Bonuses were calculated based on a secondary dataset with rating-to-bonus rules.
- Total salary (base + bonus) was computed for each employee.
- Regional bonus payout summary was generated for budgeting.

---
##  Key Strategies and Recommendations:

1. Promote Gender Balance Across Departments

Strategy: Launch targeted recruitment campaigns aimed at increasing female representation, especially in male-dominated departments like Engineering, Sales, and Manufacturing, this helps Balance teams promote innovation, collaboration, and reduce reputational risks tied to gender bias.

2. Conduct Regular Pay Equity Audits

Strategy: Implement quarterly or biannual reviews of employee salaries by gender, department, and region.

Reason: To monitor and correct any pay gaps and ensure equal pay for equal roles and experience levels.

3. Ensure Compliance with Minimum Wage Policy

Strategy: Immediately adjust salaries for employees earning below the $90,000 threshold to align with legal standards.

Reason: Avoid penalties, legal challenges, and foster fairness and employee trust.

4. Redesign Performance Evaluation Process

Strategy: Standardize and anonymize parts of the performance appraisal system to remove unconscious bias. Include diverse panels for performance reviews.

Reason: Fairer evaluations will improve morale, trust, and align rewards more closely with actual contributions.

5. Build a Transparent Bonus Framework

Strategy: Publish clear bonus rules based on performance ratings and ensure that all employees understand the criteria.

Reason: Transparency drives accountability and ensures perceived fairness in reward systems.

6. Invest in Female Talent Development

Strategy: Create mentorship programs, leadership training, and career advancement paths specifically for high-potential female employees.

Reason: To strengthen the pipeline of female leaders and close representation gaps at management levels.

7. Implement a Region-Specific HR Action Plan

Strategy: Customize HR initiatives based on regional insights (e.g., South region salary adjustments, West region gender diversity improvements).

Reason: A one-size-fits-all approach may not address the specific challenges found in each region.

8. Track and Report Diversity KPIs

Strategy: Integrate gender diversity metrics into the company’s HR dashboards and management reports.

Reason: Helps leadership stay accountable and track progress toward equity goals over time.

- These recommendations are designed to help Palmoria Group:

- Improve internal equity

- Comply with labor regulations

- Foster a more inclusive workplace culture

- And ultimately position itself as a modern, ethical, and competitive employer.

---

## Business Task and Dashboard Component

DATA USED:

📄 bonus_rules.xlsx [Download]([Palmoria Group Bonus Rules.xlsx](https://github.com/user-attachments/files/21019880/Palmoria.Group.Bonus.Rules.xlsx)
)

📄 employee_data.csv [Download]([Palmoria Group emp-data.csv](https://github.com/user-attachments/files/21019895/Palmoria.Group.emp-data.csv)
)

## File for analysis:

📄 Files for Analysis [Download Here]([Palmora_Analysis_Report_Perpetual Okolie.xlsx](https://github.com/user-attachments/files/21020107/Palmora_Analysis_Report_Perpetual.Okolie.xlsx)
)

📄 Files for Dashboard [Palmoria_Dashboard_Perpetual.Okolie-Overview.pdf](https://github.com/user-attachments/files/21054219/Palmoria_Dashboard_Perpetual.Okolie-Overview.pdf)# 

📊 Power BI Dashboard 

This Power BI dashboard provides an insightful overview of employee compensation, gender representation, salary and performance ratings across Palmoria Group. The purpose is to highlight trends, identify disparities, and inform HR strategies for equity and transparency.

<img width="748" alt="Palmoria Interactive Power BI Dashboard" src="https://github.com/user-attachments/assets/6076b325-31f0-4309-a52b-97cd1d0b0192" />


##  Overall Conclusion
- The HR data analysis conducted for Palmoria Group revealed critical gender-based disparities within the organization that require immediate strategic attention. Through in-depth exploration using Power BI, it became evident that gender imbalance, pay inequality, and inconsistent performance recognition exist across several departments and regions.

- Firstly, the analysis showed a significant skew in gender distribution, with male employees dominating several core departments, particularly in technical and leadership roles. Some departments even recorded zero female representation, which raises concerns about the company’s recruitment, promotion, and retention practices.

- Secondly, there were clear indicators of a gender pay gap, particularly in regions like the South and departments such as Engineering, where male employees consistently earned more than their female counterparts for similar roles. This violates the principle of equal pay for equal work and could expose the company to reputational and legal risks.

- Moreover, performance rating analysis indicated a trend where male employees were more frequently awarded higher ratings. Since these ratings influence both bonus allocation and career progression, the implications are substantial—female employees are not just underpaid but also undervalued in terms of recognition and reward.

- In terms of regulatory compliance, the company is not fully aligned with the newly adopted $90,000 minimum wage requirement. A considerable number of employees, especially in the South region, fall below this threshold, signaling an urgent need for salary adjustments.

- The bonus distribution analysis helped calculate fair, performance-based compensation and revealed which regions and departments require more budget attention. It also supported creating a more transparent and structured bonus framework.

Final Summary

#### Overall, the findings underscore the need for Palmoria Group to restructure its HR strategy, with a focus on gender equity, fair pay practices, and inclusive                performance management. By implementing the recommendations derived from this analysis—such as targeted hiring, equitable salary reviews, and unbiased performance           evaluations—the company can begin to rebuild trust, foster a more inclusive culture, and position itself for sustainable growth both locally and globally.
---












