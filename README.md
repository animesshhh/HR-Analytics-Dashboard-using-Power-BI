# HR-Analytics-Dashboard-using-Power-BI
This repo contains a comprehensive Power BI project for visualizing HR analytics data, providing valuable insights into employee performance rating, attrition rates, and more, which serves as a powerful tool for HR professionals to make data-driven decisions.


## Data
The dataset contains the following columns:

* `EmpID`: Employee ID  
* `Age`: Employee's age  
* `AgeGroup`: Age group category  
* `Attrition`: Employee attrition status (Yes/No)  
* `BusinessTravel`: Frequency of business travel  
* `DailyRate`: Daily rate of pay  
* `Department`: Employee's department  
* `DistanceFromHome`: Distance from home to workplace  
* `Education`: Employee's education level  
* `EducationField`: Field of education  
* `EmployeeCount`: Number of employees  
* `EmployeeNumber`: Employee number  
* `EnvironmentSatisfaction`: Employee's satisfaction with the work environment  
* `Gender`: Employee's gender  
* `HourlyRate`: Hourly rate of pay  
* `JobInvolvement`: Employee's job involvement level  
* `JobLevel`: Employee's job level  
* `JobRole`: Employee's job role     
* `JobSatisfaction`: Employee's job satisfaction level    
* `MaritalStatus`: Employee's marital status   
* `MonthlyIncome`: Employee's monthly income   
* `SalarySlab`: Salary slab like upto 5k, 5k-10k, etc.   
* `MonthlyRate`: Monthly rate of pay    
* `NumCompaniesWorked`: Number of companies the employee has worked for    
* `Over18`: Whether the employee is over 18 years old    
* `OverTime`: Whether the employee works overtime  
* `PercentSalaryHike`: Percentage increase in salary  
* `PerformanceRating`: Employee's performance rating  
* `RelationshipSatisfaction`: Employee's satisfaction with work relationships   
* `StandardHours`: Standard hours of work  
* `StockOptionLevel`: Employee's stock option level  
* `TotalWorkingYears`: Total years of work experience  
* `TrainingTimesLastYear`: Number of training sessions attended last year  
* `WorkLifeBalance`: Employee's work-life balance satisfaction  
* `YearsAtCompany`: Number of years the employee has been with the company  
* `YearsInCurrentRole`: Number of years in the current role  
* `YearsSinceLastPromotion`: Number of years since the last promotion  
* `YearsWithCurrManager`: Number of years with the current manager  

Calculated field:  
* `Attrition Count`: 'Yes' and 'No' values of Attrition column is encoded to 1 and 0 for easier calculations.
 

## Excel 
The dataset is initially provided in csv format and is used as the source for the Power BI visualizations. It contains detailed information about each employee, including demographic data, job-related information, and satisfaction levels. Data is first explored in Excel using Pivot Tables


## Power BI

### Attrition Analysis  

![Screenshot 2024-04-22 042245](https://github.com/animesshhh/HR-Analytics-Dashboard-using-Power-BI/assets/97463808/08609707-c43e-4a4d-8a98-57f30ec9ae8a)

1. **Number of Employees**

* **Insight Points**:   
  * Track changes in workforce size over time.
  * Monitor effects of hiring and attrition strategies.
* **Usefulness**: Helps in workforce planning, budgeting, and resource allocation.  


2. **Attrition Count**

* **Insight Points**:
  * Identify trends in employee turnover.
  * Highlight departments or roles with high attrition rates.
* **Usefulness**: Helps in understanding retention challenges and implementing targeted retention strategies.  


3. **Attrition Rate**

* **Insight Points**:
  * Compare attrition rates across different demographics or departments.
  * Identify factors contributing to attrition.  
* **Usefulness**: Provides insights for improving employee engagement and reducing turnover costs.  


4. **Average Age**

* **Insight Points**:
  * Understand the age distribution of the workforce.
  * Compare age demographics across departments or roles.
* **Usefulness**: Helps in workforce diversity planning, succession planning, and targeted benefits offerings.  


5. **Average Salary**

* **Insight Points**:
  * Analyze salary distribution and equity within the organization.
  * Compare salaries across departments or job roles.
* **Usefulness**: Helps in setting competitive compensation packages and addressing pay disparities.  

6. **Average Years in Company**

* **Insight Points**:
  * Understand employee tenure and loyalty.
  * Identify departments or roles with high turnover rates.
* **Usefulness**: Helps in improving employee retention strategies and enhancing organizational stability. 


7. **Attrition Analysis by Education**

* **Insight Points**:

  * Compare attrition rates among different education levels.
  * Identify whether certain education backgrounds are more likely to lead to attrition.
  * Understand the impact of education on employee retention and career advancement.


* **Usefulness**:

  * Helps in designing targeted recruitment strategies based on education qualifications.
  * Provides insights into the value of educational development programs in reducing attrition.


8. **Attrition Analysis by Job Role**

* **Insight Points**

  * Identify job roles with the highest attrition rates.
  * Understand the reasons behind attrition in specific job roles.
  * Compare attrition rates across different departments or functions.

* **Usefulness**:

  * Helps in identifying areas for job redesign or improvement in work conditions.
  * Provides insights for succession planning and talent development strategies.


9. **Attrition Analysis by Age, Years at Company, and Salary**

* **Insight Points**:

  * Identify age groups more prone to attrition.
  * Understand the impact of tenure on attrition rates.
  * Analyze whether salary levels affect attrition rates.

* **Usefulness**:

  * Helps in designing targeted retention strategies for specific age groups.
  * Provides insights into the relationship between salary satisfaction and employee retention.


### Employee Satisfaction and Performance Analysis

![Screenshot 2024-04-23 014530](https://github.com/animesshhh/HR-Analytics-Dashboard-using-Power-BI/assets/97463808/5ab51ede-2a45-43cf-b6f2-20920167157d)

1. **Average Job Satisfaction**

* **Insight Points**:
  * Monitor overall employee satisfaction levels.
  * Track changes in job satisfaction over time.
* **Usefulness**:
  * Helps in assessing the effectiveness of employee engagement initiatives.
  * Provides insights for improving workplace culture and job design.


2. **Job Satisfaction by Age Group**

* **Insight Points**:
  * Analyze job satisfaction levels across different age groups.
  * Identify any age-related trends or patterns in job satisfaction.
* **Usefulness**:
  * Helps in understanding the needs and preferences of different age demographics.
  * Provides insights for tailoring HR programs and benefits to meet the expectations of different age groups.


3. **Job Satisfaction vs. Attrition**

* **Insight Points**:
  * Explore the relationship between job satisfaction and attrition rates.
  * Identify whether lower job satisfaction leads to higher attrition.
* **Usefulness**:
  * Helps in pinpointing areas for improvement to reduce attrition rates.
  * Provides insights for implementing targeted retention strategies based on job satisfaction levels.


4. **Performance Rating over the Years**

* **Insight Points**:
  * Track changes in employee performance ratings over time.
  * Identify any trends or patterns in performance ratings.
* **Usefulness**:
  * Helps in evaluating the effectiveness of performance management systems.
  * Provides insights for identifying areas for training and development to improve performance.


5. **Job Satisfaction by Job Role**

* **Insight Points**:
  * Compare job satisfaction levels across different job roles.
  * Identify roles with higher or lower job satisfaction.
* **Usefulness**:
  * Helps in identifying areas for job redesign or improvement in work conditions.
  * Provides insights for tailoring career development and advancement opportunities.


6. **Job Satisfaction across Departments**

* **Insight Points**:
  * Analyze job satisfaction levels across different departments.
  * Identify departments with higher or lower job satisfaction.
* **Usefulness**:
  * Helps in understanding departmental dynamics and potential areas for improvement.
  * Provides insights for implementing targeted interventions to enhance job satisfaction within specific departments.



### Employee Performance and Compensation Analysis

![Screenshot 2024-04-23 014547](https://github.com/animesshhh/HR-Analytics-Dashboard-using-Power-BI/assets/97463808/a599d030-49fc-4627-9221-f4cab769f66f)


1. **Average Monthly Income**

* **Insight Points**:
  * Monitor the average monthly income of employees.
  * Track changes in income levels over time.
* **Usefulness**:
  * Helps in evaluating the competitiveness of salary packages.
  * Provides insights for salary benchmarking and budget planning.


2. **Average Performance Rating**

* **Insight Points**:
  * Analyze the average performance ratings of employees.
* **Usefulness**:
  * Helps in assessing the effectiveness of performance management practices.
  * Provides insights for identifying high-performing employees and areas for improvement.


3. **Average Job Involvement**
* **Insight Points**:
  * Evaluate the average level of job involvement among employees.
* **Usefulness**:
  * Helps in assessing employee engagement and commitment.
  * Provides insights for improving job design and employee motivation.


4. **Salary Distribution by Department**

* **Insight Points**:
  * Analyze the distribution of salaries across different departments.
  * Identify departments with higher or lower salary levels.
* **Usefulness**:
  * Helps in identifying potential disparities in salary levels.
  * Provides insights for implementing fair and competitive salary structures.


5. **Employee Count with Salary vs. Performance**

* **Insight Points**:
  * Analyze the relationship between employee count, salary levels, and performance ratings.
  * Identify any correlations between salary, performance, and workforce size.
* **Usefulness**:
  * Helps in identifying areas where higher salaries correlate with higher performance.
  * Provides insights for optimizing salary structures based on performance outcomes.


6. **Training Received vs. Performance Rating**

* **Insight Points**:
  * Analyze the impact of training on performance ratings.
  * Identify whether employees who receive more training tend to have higher performance ratings.
* **Usefulness**:
  * Helps in evaluating the effectiveness of training programs.
  * Provides insights for designing targeted training interventions to improve performance.


7. **Performance Rating by Age**

* **Insight Points**:
  * Analyze performance ratings across different age groups.
  * Identify any age-related trends or patterns in performance.
* **Usefulness**:
  * Helps in understanding the relationship between age and performance.
  * Provides insights for developing age-inclusive performance management strategies.



### Employee Compensation and Work-Life Balance Analysis

![Screenshot 2024-04-23 014628](https://github.com/animesshhh/HR-Analytics-Dashboard-using-Power-BI/assets/97463808/6287357a-740d-413e-9245-c10ffeae2858)


1. **Salary Distribution by Gender**

* **Insight Points**:
  * Analyze the distribution of salaries between male and female employees.
  * Identify any disparities in salary levels based on gender.
* **Usefulness**:
  * Helps in identifying and addressing gender pay gaps.
  * Provides insights for promoting gender equality in the workplace.


2. **Work-Life Balance of Employees**

* **Insight Points**:
  * Evaluate the work-life balance satisfaction levels of employees.
  * Identify departments or roles with higher or lower work-life balance satisfaction.
* **Usefulness**:
  * Helps in understanding employee well-being and job satisfaction.
  * Provides insights for implementing work-life balance initiatives and policies.


3. **Years at Company vs. Percent Salary Hike**

* **Insight Points**:
  * Analyze the relationship between the number of years an employee has been with the company and the percentage salary hike received.
  * Identify any trends or patterns in salary hikes based on tenure.
* **Usefulness**:
  * Helps in designing retention strategies based on salary progression.
  * Provides insights for adjusting salary hike policies based on tenure milestones.


4. **Education Field vs. Salary Hike Received**

* **Insight Points**:
  * Analyze the impact of education field on the percentage salary hike received.
  * Identify whether certain education backgrounds lead to higher salary hikes.
* **Usefulness**:
  * Helps in evaluating the value of specific education fields in career advancement.
  * Provides insights for designing targeted training and development programs based on education backgrounds.



## Conclusion

This Power BI analysis of HR data reveals crucial insights into employee demographics, job satisfaction, and performance. The visualizations help HR professionals make informed decisions to enhance workforce management, improve employee engagement, and optimize organizational performance.
