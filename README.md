"# USA_Sales_2014_2017_DM_Project" 
USA_Sales_Retail_DataManagement_Project

Project Overview

This project processes USA retail sales data, ensuring quality, consistency, and usability. The workflow transforms raw data into a clean, structured format, maintains dynamic file structuring, integrates processes, and provides insights through analysis and visualization.

Main Research Question: Do public holidays in the United Kingdom significantly affect daily e-commerce sales volume in 2011?

Sub-questions:

Are sales higher on holidays compared to non-holidays?
Which USA holidays have the greatest impact on daily sales?
Which days in 2011 experienced the highest e-commerce sales, and were they holidays?
Can holiday information improve basic sales predictions?
Steps in the Project

Import Libraries: Load Python libraries for data handling (pandas, numpy) and visualization (matplotlib, seaborn).

Dynamic File Structuring: Dynamic File structures are created for easy accessing purpose

Data Acquistion: Source 1: Read the Excel file containing retail transactions into a DataFrame. (UCI) Source 2: Web API for USA holidays in 2011 https://date.nager.at/

Initial Exploration: Inspect data shape, column names, and sample records. Check for missing values and basic statistics.

Data Cleaning: Handle missing or null values. Correct inconsistent entries. Convert data types where needed

Queries & Integration Process: Extract insights by filtering, grouping, and summarizing data. Integrated different datasets to ensure a smooth workflow.

Quality Checks: Validate the cleaned data for accuracy and consistency before further processing.

Data Storage: Save cleaned and Integrated Dataset in sqllite DB

Data Analysis & Visualization: Explore trends, top-selling products, and store performance using seaborn and matplotlib Generate graphs and plots to answer research questions.

#Maintained in Github
