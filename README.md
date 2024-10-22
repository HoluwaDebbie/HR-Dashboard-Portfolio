# LITA-PowerBI-Documentation

## Project Title: HR Attrition and Satisfaction Analysis Using Power BI and DAX
---

[Project Overview](#project-overview).

[Data Sources](#data-sources).

[Tools Used](#tools-used).

[Data Cleaning and Preparations](#data-cleaning-and-preparations).

[Exploratory Data Analysis](#exploratory-data-analysis).

[DAX Calculations](#dax-calculations).

[Dashboard](#dashboard).

[Visualization](#visualization).

[Conclusion](#conclusion).

[Key Skills Demonstrated](#key-skills-demonstrated).


### Project Overview

In this project, I analyzed employee attrition and satisfaction data to identify critical trends within a company’s workforce. My goal was to understand the main drivers behind employee attrition, measure employee satisfaction across various departments, and explore how business travel, job roles, and other factors affect these outcomes. The insights generated provide actionable recommendations for improving employee retention and engagement.

---

### Data Sources

The data for this analysis comes from the **HR data.xlxs** file, which was freely downloaded from **Kaggle.com**.

---

### Tools Used:

For this project, I leveraged the following tools:
1. **Power BI**: Data visualization and dashboard creation.
2. **DAX (Data Analysis Expressions)**: Performed advanced calculations, including attrition rate, average age by department, and satisfaction scores.
3. **Excel**: Initial data cleaning and exploration.
4.**Power Query**: Used for data transformation and ensuring data consistency.
5. **Github**: Used for portfolio building.

---

### Data Cleaning and Preparations

The dataset I worked with was clean and consistent, requiring minimal preprocessing. Using **Power BI’s column profiling tools** (*Column Quality, Column Distribution, and Column Profile*), I ensured the dataset was free from missing or erroneous values. These tools verified that the data was 100% consistent, allowing me to dive directly into the analysis.

---

### Exploratory Data Analysis

EDA involves understanding the data and extracting initial insights to guide further analysis. Based on my dataset, I explored the following key questions:

- How many employees rarely travel for business?

- What is the attrition rate across departments, and which department has the highest?
 
- How does business travel frequency affect attrition?
 
- What is the average employee age by department?
 
- What is the overall satisfaction index across departments?

---

### DAX Calculations:
To dive deeper, I employed several DAX calculations to uncover meaningful insights:
1. **Attrition Rate**: I calculated the overall attrition rate by dividing the number of employees who left by the total workforce, arriving at a 16% attrition rate.
2. **Attrition by Department**: The highest attrition rates were found in the Research & Development (R&D) department, indicating a need for further investigation into the work culture there.
3. **Business Travel & Attrition**: Employees who rarely travel had a significantly higher attrition count (156 employees) than frequent travelers (69), suggesting that travel flexibility might be a retention factor.
4. **Average Age by Department**: The HR department had the highest average age, which may influence how work is structured.
5. **Satisfaction Index**: R&D reported the lowest satisfaction score at 2.73, highlighting areas for improvement.

In addition, the salary hike percentage was calculated to be **100%**, indicating that all employees had received a salary hike, though further analysis is needed to determine the distribution of those hikes.

---

### Dashboard

**Dashboard 1: Employee Attrition Overview**

**Objective**: Provide a comprehensive view of overall and departmental attrition rates, analyzing how the department, business travel, gender, and job roles contribute to employee turnover.

 **Visual 1: Attrition by Department**
 
 - **Type**: Clustered Bar Chart
 
 - **X-Axis**: Department
 
 - **Y-Axis**: Count of employees with Attrition = Yes
 
 - This chart highlights the departments with the highest attrition rates, showing that the R&D department has the highest turnover rate.

**Visual 2: Attrition by Business Travel**

- **Type**: Clustered Column Chart

- **Legend**: Business Travel (Frequently, Rarely, Non-Travelers)

- **Y-Axis**: Count of employees with Attrition = Yes

- It demonstrates that employees who rarely travel for business have significantly higher turnover rates than frequent travelers or non-travelers.

**Visual 3: Attrition by Gender**

- **Type**: Stacked Column Chart

- **X-Axis**: Gender

- **Y-Axis**: Count of employees with Attrition = Yes

- It shows that male employees have a higher attrition rate than female employees, with more male employees leaving the company.

**Visual 4: Attrition by Job Role**

- **Type**: Clustered Column Chart

- **X-Axis**: Job Role

- **Y-Axis**: Count of employees with Attrition = Yes

- This chart reveals that laboratory technicians experience the highest attrition, while research directors have the lowest turnover rate, indicating differences in attrition based on job roles.

**Dashboard 2: Employee Satisfaction & Experience**

**Objective**: Analyze employee satisfaction levels and overall experience across various metrics.

**Visual 1: Satisfaction Index by Department**

- **Type**: Clustered Bar Chart

- **X-Axis**: Department

- **Y-Axis**: Satisfaction Index

- This chart displays employee satisfaction levels by department, highlighting that the R&D department has the lowest satisfaction score.

**Visual 2: Average Age by Department**

- **Type**: Clustered Column Chart

- **X-Axis**: Department

- **Y-Axis**: Average Age

- Shows the average age of employees across different departments, with HR having the highest average age, suggesting that it has the most experienced staff.

**Visual 3: Work-Life Balance vs Job Satisfaction**  

  - **Type**: Scatter Plot
    
  - **X-Axis**: Job Satisfaction
     
  - **Y-Axis**: Work-Life Balance
     
  - **Legend**: Department
     
  - This scatter plot illustrates the relationship between work-life balance and job satisfaction, with each point color-coded by department to show how these factors vary across different teams.

**Visual 4: Salary Hike Percentage**  

  - **Type**: Pie Chart
    
  - Displays the percentage of employees receiving salary hikes more significantly than 10%. The result shows that 100% of employees received a salary hike, though the extent of the increases varied across the workforce.

---

### Visualization

[My Calculations](https://github.com/user-attachments/assets/de42bb53-b09b-4da8-b54f-8f2d6e9db54a)

[Dashboard 1](https://github.com/user-attachments/assets/e1768eb1-ed5c-47b2-9de8-8f2e4520e8a1)

[Dashboard 2](https://github.com/user-attachments/assets/8b2e1615-259b-40e7-b3b4-731eed5129a6)

---


### Conclusion:

This analysis revealed that the R&D department needs to work on retaining employees, especially those who rarely travel. Improving work-life balance, increasing satisfaction, and tailoring HR policies to departments' unique needs could reduce attrition rates. These findings provide a solid foundation for strategic HR initiatives to enhance employee retention and overall workplace satisfaction.

---

### Key Skills Demonstrated:

1. Data Analysis and Visualization using Power BI to communicate key insights.
2. Use DAX to create advanced measures such as Attrition Rate, Satisfaction Index, and Average Age by Department.
3. Data Cleaning and Transformation through Power Query to ensure the dataset was ready for analysis.
4. Portfolio building and project showcase through GitHub, highlighting a polished project with actionable business insights.
   
This project showcases my skills in handling HR data, delivering valuable insights through DAX calculations and creating interactive visualizations that aid decision-making.

---

