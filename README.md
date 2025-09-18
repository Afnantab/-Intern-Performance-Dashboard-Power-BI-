
# 👩‍💻 Intern Performance Dashboard – Power BI  

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)  
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-Power%20Query-blue.svg)  
![DAX](https://img.shields.io/badge/DAX-Analysis-orange.svg)  

## 📌 Overview  
The **Intern Dashboard** provides insights into **intern performance, tasks, attendance, and completion rates**.  
It was built in **Power BI** after data cleaning in **Power Query** and advanced calculations in **DAX** (including grouping, completion rate calculations, and custom measures).  

This dashboard helps HR and managers track intern productivity and performance across different departments.  

---

## 📊 Key Metrics & KPIs  

- **Average Score:** 3.53  
- **Average Time per Task:** 2.48 hrs  
- **Total Overtime Hours:** 3K  
- **Total Completion Rate:** 81.01K (67.51% average)  
- **Total Interns:** 1.20K  
- **Total Tasks Assigned:** 12K  
- **Total Attendance:** 102K  

### 📈 Departmental Insights  
- **Completion Rate by Department:**  
  - Finance: 100%  
  - Marketing: 42.9%  
  - Sales, R&D, IT, Operations, HR: Varied between ~40–80%  

- **Tasks Completed by Department:**  
  - Finance: 1,435  
  - Marketing: 1,433  
  - Sales: 1,314  
  - R&D: 1,261  
  - IT: 978  
  - Operations: 971  
  - HR: 621  

- **Teamwork Contribution by Department:**  
  - Marketing: 18.46%  
  - Finance: 16.42%  
  - Sales: 16.36%  
  - R&D: 15.89%  
  - Operations: 12.74%  
  - IT: 12.33%  
  - HR: 7.79%  

---

## 🛠️ Data Preparation  
### 🔹 Power Query (ETL Steps)  
- Cleaned raw intern performance data  
- Removed duplicates & nulls  
- Split and merged columns for attendance and task records  
- Standardized formats for dates and task measures  

### 🔹 DAX (Data Analysis Expressions)  
- Created measures for **Completion Rate**, **Average Score**, **Teamwork %**  
- Used **GROUPBY** for department-level aggregations  
- Applied filters for **weekly task assignment trends**  

---

## 📂 Repository Structure  
