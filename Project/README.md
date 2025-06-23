# Project 2 Analysis
## Introduction
This project aims to explore and understand the skills most frequently requested by top employers in today's job market. Using Excel for data cleaning, visualization, and analysis.
By uncovering these trends, this project can help job seekers make informed decisions about which skills to develop in order to boost their employability and earning potential.
## Questions to Analyze

To understand the data science job market, this project explores the following questions:

- **Do more skills get you better pay?**  
- **What’s the salary for data jobs in different regions?**  
- **What are the top skills of data professionals?**  
- **What’s the pay for the top 10 skills?**  
##  Excel Skills Used

The following Excel skills were utilized for analysis:

- 📊 **Pivot Tables**
- 📈 **Pivot Charts**
- 🔖 **DAX (Data Analysis Expressions)**
- 🔍 **Power Query**
- 💪 **Power Pivot**

## Data Jobs Dataset

The dataset used for this project contains real-world data science job information from 2023. The dataset is available via an Excel course, which provides a foundation for analyzing data using Excel.

It includes detailed information on:

- 👨 **Job titles**  
- 💰 **Salaries**  
- 📍 **Locations**  
- 🛠️ **Skills**
## 1. Do More Skills Get You Better Pay?

### 🔍 **Skill Spotlight: Power Query (ETL Process)**

### 📥 Extract  
I used Power Query to import the original dataset (`data_salary_all.xlsx`) and created two separate queries:
- 🗃️ One containing all data job listings and relevant details.  
- 🔧 Another breaking down the individual skills associated with each job ID.

### 🔄 Transform  
Each query was refined by:
- Adjusting column data types  
- Removing unnecessary fields  
- Cleaning up text (e.g., removing specific keywords)  
- Trimming extra spaces for consistency and accuracy
 - #### 📊 `data_jobs_all`
This query contains all job-related information, including job titles, salaries, locations, and more.

![Project Analysis Screenshot 1](Excel_Project-Data_Anlystics\0_Resources\Images\2_Project_Analysis_Screenshot1.png)

---

 - #### 🛠️ `data_job_skills`
This query focuses on the extracted skills for each job ID, allowing for detailed skill-based analysis.

![Project Analysis Screenshot 2](2_Project_Analysis_Screenshot2.png)
### 🔗 Load

After transforming the data, I loaded both queries into the Excel workbook to prepare for in-depth analysis.

#### 📊 `data_jobs_all`  

![Data Jobs All Load Screenshot](Excel_Project-Data_Anlystics\0_Resources\Images\2_Project_Analysis_Screenshot1.png)

![Data Jobs All Load Screenshot](0_Resources/Images/2_Project_Analysis_Screenshot1.png)


---

#### 🛠️ `data_job_skills`  

![Data Job Skills Load Screenshot](2_Project_Analysis_Screenshot4.png)
## 📊 Analysis

### 💡 Key Insights

- 📈 There is a clear upward trend showing that jobs requiring a greater number of skills often offer higher median salaries. This pattern is especially noticeable in positions such as **Senior Data Engineer** and **Data Scientist**.

- 💼 In contrast, roles with fewer skill requirements—such as **Business Analyst**—typically come with lower salary ranges. This suggests that possessing a broader or more specialized skill set significantly enhances earning potential in the data field.
