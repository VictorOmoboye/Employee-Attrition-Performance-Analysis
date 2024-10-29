# EMRALD TECH EMPLOYEE ATTRITION PERFORMANCE ANALYSIS
## Leveraging SQL-based descriptive and diagnostic analytics in understanding the demographic and job-related factors driving employee turnover.
![image](https://github.com/user-attachments/assets/e8fcd740-02ee-4970-82a9-7d26ee312ac6)
## INTRODUCTION
**Emerald Technologies**, a leading multinational mobile telecommunications company, operates across numerous African and Asian countries. As of December 2022, it recorded 1 billion subscribers, making it the 3rd largest mobile network operator globally and the largest in Africa and Asia. Despite its market dominance, Emerald Technologies faces challenges related to employee attrition and performance management. This project aims to address these challenges by leveraging SQL-based descriptive and diagnostic analytics to analyze employee data. By uncovering key demographic and job-related factors driving turnover, assessing the fairness of promotion policies, and identifying targeted training opportunities, the analysis will provide actionable insights to reduce attrition, enhance employee satisfaction, and optimize training and promotion processes—ultimately fostering a more productive and engaged workforce.
## PROBLEM STATEMENT
**Emerald Technologies** is facing challenges  related to employee attrition and performance management. There is a pressing need to better understand the factors contributing to employee turnover, to ensure that our promotion policies are fair and effective , and to optimize training programs to enhance employee performance and satisfaction.
## AIM OF THE PROJECT
- **Analyze Employee Demographics:** Examine demographic profiles to understand diversity and inclusion within the organization.

- **Identify Attrition Factors:** Uncover key demographic and job-related factors contributing to employee turnover.

- **Enhance Promotion Policies:** Assess and improve the fairness and effectiveness of promotion processes.

- **Optimize Training Programs:** Provide targeted training opportunities to improve skills, performance, and employee satisfaction.

## METHODOLOGY
- **Business Understanding:** Understand the company's objectives and expectations to align analysis with business goals.
- **Data Extraction:** Retrieve Employee Performance and Employee Test data from the company's database for in-depth analysis.
- **Develop Analysis Approach:** Define a clear plan for the analysis, identifying key metrics and setting objectives aligned with the business goals.
- **Perform Descriptive Analysis:** Use SQL queries to summarize data, identify trends, and generate an overview of employee demographics, attrition rates, and performance metrics.
- **Perform Diagnostic Analysis:** Dive deeper into the data to identify the factors driving attrition and variations in performance, correlating demographic and job-related elements to employee turnover and productivity.
**Generate Insights and Recommendations:** Based on findings from the analyses, provide actionable insights and recommendations to address employee attrition, enhance promotion policies, and optimize training programs.

## SQL TOOLS AND FEATURES
- **SQL QUERIES:** Extract relevant data from the Employee Performance and Employee Test tables.
- **CASE:** Executes conditional logic by evaluating conditions and returning a value.
- **JOIN:** Combine rows from two or more tables based on a related column between them.
- **COALESCE:** Returns the first non null value from a list of arguments.
- **CAST:** Converts a value from one data type to another.

## MODELLING
To understand the structure of the database, I visualise the Entity-Relationship Diagram (ERD) that maps out the tables and their connections. This diagram clarifies how the tables, **employee performance** and **employee test**, are organized and interact with each other. Using the ERD as a guide, I can see how data flows between these tables, making it easier to analyze employee performance and identify factors influencing attrition and training needs. This clear structure is essential for accurate and effective analysis throughout the project.
![image](https://github.com/user-attachments/assets/80957a68-7ff4-4858-a490-d69920468129)

## DATA ANALYSIS
This query provides a comprehensive view of the **employee performance** and **employee test tables**, enabling a clear visualization of key metrics and attributes essential for analyzing employee performance, attrition factors, and training effectiveness.
![image](https://github.com/user-attachments/assets/5887a408-c817-40dd-8bb5-5242a1943714)


### Descriptive Analytics (Employee Demographic)
This query provides insights into the organization's workforce by displaying the total number of employees (1,470) and identifying the maximum tenure, which stands at 31 years. It also breaks down employee counts by department, highlighting that Sales and Marketing have the highest number of employees (446), followed by Operations (291). In contrast, R&D and Legal have the fewest employees, with 29 and 30, respectively. This analysis offers a clear view of departmental distribution and tenure, valuable for understanding team structures and workforce composition.
![image](https://github.com/user-attachments/assets/ef30f5e8-eaa7-41cc-a6d4-faeb81484c70)


The first query illustrates the gender distribution of employees, indicating that males comprise the majority with a count of 1,069, while females account for 401. Additionally, the second query categorizes employee ages into five distinct groups, revealing that the age group of 30-39 has the highest representation with 749 employees, whereas only 7 employees are aged 60 and above. This analysis provides valuable insights into the demographic composition of the workforce.
![image](https://github.com/user-attachments/assets/1ff335d2-4e47-43d9-aef1-4decb4b97773)

### Diagnostic Analytics (Employee Performance)
This diagnostic analysis focuses on employee performance regarding training scores. The first query identifies the highest average training score, which is achieved by only two employees, both scoring 97. The second query examines the average training scores across departments, revealing that the R&D and Analytics departments lead with scores of 84.83 and 84.82, respectively. In contrast, the Sales and Marketing department has the lowest average score at 49.84. These insights are crucial for identifying areas for improvement in training and development initiatives.
![image](https://github.com/user-attachments/assets/cde9360a-906e-4386-bf01-9462a611d118)



This query reveals the average training scores of employees based on their education levels, indicating that those with a Master's degree or higher have the highest average score of 65.0, followed by employees with a Bachelor's degree at 63.3. In contrast, employees with an N/A designation have the lowest average score at 57.9. The second query highlights the average performance ratings from the previous year by recruitment channel, showing that employees recruited through referrals received the highest rating of 3.82, followed by those sourced through other channels, which averaged a rating of 3.32. These findings provide valuable insights into the relationship between education, recruitment channels, and employee performance.
![image](https://github.com/user-attachments/assets/e9404235-7494-43b8-812f-0f4b8754343e)



This query categorizes the average training scores into grades (A, B, C, D, E, F) based on age groups while also revealing the average performance ratings from the previous year. The results show that 775 employees received an A grade, indicating a strong performance, whereas only 15 employees were assigned an E grade, reflecting significantly lower scores. This analysis highlights the distribution of training performance across different age groups and underscores the need for targeted support for lower-performing employees.
![image](https://github.com/user-attachments/assets/e307820e-47e7-4987-bead-840d3837a104)


### Diagnostic Analytics(Employee Attrition)
The first query reveals that the average attrition rate across the organization is 0.161. The second query identifies the regions with the highest rates of employee departures, showing that Region 2 has the highest attrition rate, with 46 departures. Following this, Region 22 reports 24 departures, while Regions 24 and 12 have no attrition at all. These insights are crucial for understanding regional turnover dynamics and informing targeted retention strategies.
![image](https://github.com/user-attachments/assets/5282ebb1-1267-49c1-9bb4-32fe8b7f002f)



The first query identifies the departments with the highest average job satisfaction ratings, revealing that the Human Resources department has the highest rating at 2.91, followed closely by Legal at 2.87. In contrast, the Research and Development department has the lowest job satisfaction rating at 2.38. Additionally, the second query highlights the departments with the highest rates of employee departures, indicating that Sales and Marketing has the highest turnover rate, with 73 departures, followed by Operations. Meanwhile, both R&D and HR report the lowest attrition rates, with only 5 departures each. These findings provide valuable insights into employee satisfaction and retention challenges across different departments.
![image](https://github.com/user-attachments/assets/20686105-33bf-4a14-8a0c-251635eee9fd)


## RECOMMENDATION
Based on the insights drawn from the **employee performance and employee test** datasets, here are some data-driven recommendations to help control employee attrition at **Emerald Technologies:**

- **Enhance Job Satisfaction Initiatives**: Since the HR department reported the highest job satisfaction rating, consider leveraging their practices across other departments. Implement regular feedback mechanisms, employee engagement surveys, and recognition programs to boost morale and job satisfaction in lower-rated areas like R&D.
  
- **Focus on Employee Training and Development**: With lower average training scores in some departments, enhance training programs to ensure employees have the necessary skills and support to excel. Tailor training initiatives based on performance ratings and feedback, particularly for those with lower scores, to increase engagement and reduce turnover.

- **Targeted Retention Strategies for High-Turnover Departments**: Given that Sales and Marketing have the highest attrition rate, develop specific retention programs for these departments. This could include career development opportunities, competitive compensation packages, and targeted mentorship programs to support employee growth and satisfaction.

- **Strengthen Recruitment Practices**: Since employees hired through referrals received higher ratings, encourage current employees to refer potential candidates. This could lead to improved cultural fit and job satisfaction, thereby reducing attrition rates.

- **Analyze Regional Disparities**: Address the high attrition rate in Region 2 by conducting exit interviews to understand the underlying causes of departures. Tailor retention strategies to the unique challenges faced in that region, such as work-life balance, managerial support, or local market conditions.

- **Regular Performance Reviews**: Implement structured performance reviews that focus on employee development and provide actionable feedback. This can help employees feel more engaged and valued, reducing the likelihood of attrition.

- **Implement Flexible Work Options**: To enhance job satisfaction and attract diverse talent, consider offering flexible work arrangements or remote work options, especially in departments with lower satisfaction ratings.

By applying these recommendations, **Emerald Technologies** can create a more supportive work environment that addresses the root causes of attrition and enhances overall employee satisfaction.

## THANK YOU
For more information, you can contact me
![image](https://github.com/user-attachments/assets/c5adc252-19dd-483b-adbd-339b1eb14fad)
