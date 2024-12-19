# Alliance_Employee_Analysis

## Table Of Content
- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
  
## Project Overview
This data analysis project provides insights into the alliance employee's dataset 


![youtube pic](https://github.com/user-attachments/assets/cda4c954-b19d-4ee2-bd28-3df2281b8bd2)


#### Data source
The primary dataset used for this project is "dataset_for_excel_powerbi" from ChatGPT.

#### Tools
- Excel(Data Cleaning)
- Power Bi(Data Analysis, Creating Report)

#### Data Cleaning/Preparation
We performed the following tasks for the preparation phase:

1. Data loading.

2. Handling missing values

3. Cleaning data.

#### Exploratory Data Analysis

This involved exploring the dataset_for_excel_powerbi to answer questions, such as:
1. Demographic Analysis
2. Salary and Experience
3. Satisfaction and Performance
4. Gender and Promotion Analysis
5. Comparative Analysis
6. Key Insights



#### Data Analysis
Using the power query I replaced some values to calculate better.

Created a Dax function
```powerbi
COUNTA(dataset_for_excel_powerbi[Name])
```

#### Results/Findings

The Analysis Results are Summarised as follows:

- Salaries for female employees are 15% lower than male employees in the same role within IT department.

- Employees not promoted in over 5 years show declining performance.

- Total number of employees: 10k.

- Male employees are promoted at a 20% higher rate than female employees despite similar performance ratings.

-  Promoted employees have a higher likelihood of leaving if salary increases do not accompany the promotion.
  

#### Recommendation

Based on the analysis, we recommend the following actions:

- Align promotions with competitive salary adjustments to improve retention.

- Invest in team-building activities and cross-functional projects to enhance collaboration across all departments.

- Initiate targeted recruitment and mentorship programs to improve gender representation in the R&D department.

- Introduce performance-based salary increments for experienced employees to boost morale and retention.

#### Limitations

- The analysis shows relationships (e.g., between salary and satisfaction) but cannot prove causation without deeper investigation or controlled experiments

- Missing records for key variables (e.g., satisfaction scores, years of experience) lead to biased conclusions.

- Personal circumstances (e.g., health, family issues) can affect metrics like performance or satisfaction but are not captured in the data.


