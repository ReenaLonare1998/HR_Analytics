# HR Analytics Dashboard

This repository contains an HR Analytics Dashboard designed to provide an overview of key HR metrics, helping organizations to analyze employee attrition, demographic patterns, and performance-related trends. This dashboard is aimed at assisting HR teams in identifying areas that require attention and helping them to make data-driven decisions.



## Project Overview

The HR Analytics Dashboard enables users to explore key HR metrics such as employee attrition, salary distribution, and demographic trends. It breaks down attrition rates by education, age group, salary brackets, and job role. The dashboard is interactive and dynamic, allowing users to filter data based on department and job role, which enhances the usability of the insights provided.
## Features


* Employee Count: Total number of employees analyzed.
* Attrition Rate: Breakdown of attrition across various demographics and categories.
* Salary Analysis: Average salary and salary-based attrition rates.
* Age Distribution: Attrition rates across different age groups.
* Education-Level Attrition: Insights on attrition based on education background.
* Job Role-Based Attrition: Identifying roles with higher attrition rates.
* Years of Service Analysis: Attrition rates based on employee tenure.
## Tools and Technologies

This project uses the following tools and technologies:

* Power BI: To build and visualize the HR Analytics Dashboard.
* Power Query: Used for data cleaning and transformation.
## Key Performance Indicators (KPI's)


### 1. Overall Metrics
* Total Employee Count: 1,470 employees.
* Total Attrition Count: 237 employees, resulting in an attrition rate of 16.1%.
* Average Age: Employees have an average age of 37 years.
* Average Salary: The average salary across the organization is 6.5K.
* Average Experience (Years): On average, employees have 7 years of service.


### 2. Attrition by Education
* Life Sciences: Accounts for 38% of the total attrition.
* Medical: Responsible for 27% of attrition.
* Marketing: Contributes to 15% of attrition.
* Technical Degrees: Makes up 5% of the attrition.

### 3. Attrition by Age
* The highest attrition rate is seen among employees aged 26-35 years, accounting for 116 employees.
* 44 employees aged 18-25 years left the company, followed by 43 employees aged 36-45 years.
* Attrition among employees aged 55+ years is significantly lower at 8 employees.

### 4. Attrition by Salary Slab
* The majority of attrition comes from employees earning less than 5K, with 163 employees leaving the organization.
* Employees earning between 5K-10K account for 49 departures.
* Only 5 employees earning more than 15K have left the company.

### 5. Attrition by Years at Company
* The highest attrition occurs in the first 0-1 years, with 59 employees leaving.
* Employees with 1-2 years of tenure show a sharp decline in attrition, with 19 employees leaving.
* Attrition further decreases for employees with 3-5 years of experience (only 8 departures).

### 6. Attrition by Job Role
* The highest attrition is seen in Laboratory Technicians, with 62 employees leaving.
* Sales Executives and Research Scientists follow closely with 57 and 47 employees, respectively.
* Sales Representatives have an attrition count of 33.

### 7. Gender-Based Attrition
* 140 Male employees have left the organization, compared to 79 Female employees.
## Conclusion

The HR Analytics Dashboard highlights key areas for improvement, such as high attrition among employees with less than a year of service and those in lower salary brackets. Mid-career professionals (ages 26-35) and specific roles like Laboratory Technicians and Sales Executives also show elevated attrition rates. Addressing these issues can lead to better retention and overall workforce stability.
## How to Use

#### 1.  Clone the repository to your local machine:
```bash
  git clone https://github.com/ReenaLonare1998/HR_Analytics.git
```

#### 2. Open the Power BI file:

* Download and install **Power BI Desktop**.
* Open the HR_Analytics_Dashboard.pbix file.

#### 3. Load the CSV Data:

* Go to the Home tab and click Get Data.
* Select Text/CSV and upload the **HR_Analytics.csv** file.
* Ensure the data loads correctly and corresponds to the fields in the dashboard.
#### 4. Transform the Data (if necessary):

* Go to the Home tab in Power BI and click Transform Data to open Power Query Editor.
* In the Power Query Editor, you can:
    * Filter rows (e.g., exclude certain departments or age groups).
    * Rename columns or adjust data types (e.g., convert text to numbers).
    * Merge or append data from other sources.
    * Create calculated columns for new insights (e.g., calculate tenure from start date).
* Once the data is transformed as needed, click Close & Apply to save the changes.
#### 5. Explore the Dashboard:

* Use filters for department and job role to explore different segments.
* Hover over visuals to see detailed insights on attrition, salary distribution, and employee demographics.




Feel free to dive in, explore the data, and customize the dashboard to suit your needs. Should you have any feedback or questions, don’t hesitate to get in touch.

Enjoy analyzing the data!
