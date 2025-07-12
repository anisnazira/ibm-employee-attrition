# ibm-employee-attrition
This project analyzes the IBM Employee Attrition dataset using exploratory, descriptive, predictive, inferential, causal, and mechanistic analysis to uncover key patterns and drivers of employee turnover, offering insights into factors that influence attrition.

<p align="center">• ────── ✧ ────── •</p>

## 📊 Business Case

**Executive Summary**

- In today's post-pandemic workforce, employee retention has emerged as one of the top concerns for organizations globally. According to Meritt Recruitment, citing data from the Work Institute, the global employee turnover rate climbed to around 20% in 2024, up from 18% in 2023. This increase underscores the challenges organizations encounter in maintaining employee retention. Understanding the factors that drive employee attrition is critical for especially for HR departments to develop data-driven retention strategies. High attrition leads to increased recruitment and training costs, productivity loss, and disruption in team dynamics. 
This analysis aims to investigates the relationship between employee attrition and key influencing factors such as work-related features, compensation, demographics and career trajectory. By uncovering patterns in these variables, I aim to identify high-risk employees, understand root causes of turnover, and recommend actionable retention strategies.

**Objective**

- The primary goal of this analysis is to gain actionable insights of how different employee attributes and workplace factors influence the likelihood of attrition.

## ❓ Data Science Questions

**Exploratory analysis**

1. What are the patterns and relationships among work-related factors for Gen Z employees, including monthly income, work life balance, job satisfaction, environment satisfaction, relationship satisfaction, distance from home, years at company and their connection to attrition?

2. Which specific departments and job roles are most affected by high attrition rates?

3. What are the overall patterns in attrition across different demographic groups, and how do Gender, Age, and MaritalStatus interact with WorkLifeBalance?

**Descriptive analysis**

4. What are the average MonthlyIncome, PercentSalaryHike, overtime for employees with and without attrition? 

5. What are the distributions of EnvironmentSatisfaction, RelationshipSatisfaction, and JobInvolvement for employees across various job roles and departments?
give code for this


**Predictive analysis**

6. How do DailyRate, DistanceFromHome, JobInvolvement, JobLevel, MonthlyIncome, NumCompaniesWorked, OverTime status, PercentSalaryHike, PerformanceRating, TotalWorkingYears, WorkLifeBalance, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrManager, and BusinessTravel frequency influence employee attrition?


**Inferential analysis**

7. Is there a statistically significant difference in JobLevel, YearsAtCompany, Training Times Last Year, YearsatCompany, Years Since Last Promotion between employees who left and those who stayed? 

**Causal analysis**

8. How does improved WorkLifeBalance and reduced OverTime causally affect attrition among employees with high DistanceFromHome? (understand relationship demographic and workload)

**Mechanistic analysis**

9. What is the mechanism by which BusinessTravel, JobInvolvement, and TrainingTimesLastYear affect the probability of leaving? 



## 🧠 Summary



- Based on the analysis, this large company's primary problem is high employee attrition, particularly in specific job roles like Sales Representatives, Laboratory Technicians, Human Resources, Sales Executives, and Research Scientists. This attrition is driven by a combination of factors.A critical finding is the significant impact of overtime. Employees who work excessive overtime are more than twice as likely to leave, indicating severe burnout and work-life balance issues. This is especially problematic for male employees, who show a steeper decline in attrition as work-life balance improves. The analysis also highlights that lower base salaries are a critical driver of attrition, even more so than salary hikes. Employees earning between RM2,000 and RM3,000 are notably more likely to leave.Furthermore, job involvement is a another factor. Employees with low job involvement (scoring 1 or 2) are significantly more likely to leave, indicating a lack of connection or engagement with their roles. Business travel, especially frequent travel, also contributes to attrition, likely due to stress and an imbalance between work and personal life. Finally, a lack of training and development opportunities contributes to employees feeling stagnant and seeking opportunities elsewhere, particularly for those with less than two years tenure. Years since last promotion also significantly impacts an employee's decision to leave.According to Randstad Malaysia’s Employer Brand Research report, 24% of Malaysian workers believe that a lack of training opportunities and insufficient managerial support are key contributors to employee disengagement and attrition despite 85 per cent of respondents said that upskilling and re-skilling is important to them. Addressing these issues could help companies improve retention by focusing on career development and employee support (Randstad HR Trends 2023).To combat this, HR should implement targeted strategies such as strengthen Career Development. This is a crucial area. Create clear, transparent career pathways with opportunities for growth and promotion.The least problematic area for this company appears to be overall relationship satisfaction among employees. While some roles like Laboratory Technician show a slight dip, generally, employees report high satisfaction with their relationships at work. This indicates a positive and friendly work culture where individuals mostly get along.


## 📚 References

1. Li Qi, Cheok Mui Yee, Benjamin Chan Yin Fah, The Role of Work-Life Balance in Enhancing Employee Loyalty. Accounting and Corporate Management (2024) Vol. 6: 43-47. DOI: http://dx.doi.org/10.23977/acccm.2024.060106.

2. Merritt Recruitment. (2024, July). Staff retention in 2024: Global stats and trends. Merritt Recruitment. Retrieved from https://www.merrittrecruitment.com/blog/2024/07/staff-retention-in-2024-global-stats-and-trends

3. Pavansubhasht. (2017, January 5). IBM HR Analytics Employee Attrition & Performance [Dataset]. Kaggle. Retrieved July 1, 2025, from https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

4. Racolța-Paina, Nicoleta & Irini, Radu. (2021). Generation Z in the Workplace through the Lenses of Human Resource Professionals – A Qualitative Study. Quality - Access to Success. 22. 78-85. 

5. Randstad Malaysia. (2023). Employer brand research: HR trends report. Randstad. Retrieved from https://www.randstad.com.my/hr-trends/employer-brand/24-per-cent-malaysians-lack-training-opportunities-support/
