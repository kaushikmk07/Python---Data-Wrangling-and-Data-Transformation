📊End-to-End ETL & Data Wrangling: Project Financials Analysis  (Python)

Developed in: Jupyter Notebook | Stack: Pandas, NumPy | Framework: ETL & Business Logic Automation

📌 Project Overview

This project involves an end-to-end data pipeline to process corporate project and employee data. The primary objective was to take raw, disconnected datasets and apply complex business rules for financial bonuses and HR performance tracking.

🛠️ Key Technical Implementations

Based on the project requirements, I implemented several advanced data handling techniques in a Jupyter Notebook environment:


* Data Cleaning (Task 2): Addressed missing values in project costs using a custom running average algorithm implemented via a For loop.


* Relational Data Merging (Task 4): Unified three separate tables (Project, Employee, and Seniority) into a master dataframe titled "Final".


* Financial Feature Engineering (Task 5): Automated the calculation of a 5% bonus for all projects with a "Finished" status.

* HR Logic Automation (Tasks 6 & 8):

* Programmed demotions for failed projects and enforced eligibility rules by removing records with a designation level above 4.
+1

* Applied promotions using conditional IF statements for employees over the age of 29.


* String Manipulation (Tasks 3 & 7): Refactored employee names into "First" and "Last" name columns and applied gender-based professional titles ("Mr."/"Mrs.").
+1


* Data Aggregation (Task 9): Generated a new reporting dataframe, TotalProjCost, summarizing total expenditures by employee
