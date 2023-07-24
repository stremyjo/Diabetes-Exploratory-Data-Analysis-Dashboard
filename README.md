# Diabetes Exploratory Data Analysis Project

Welcome to the Diabetes Exploratory Data Analysis Project repository! This project involves data cleaning and analysis of diabetes-related data. Below, you will find details about the project, the original dataset, the codebook used for recoding values, and the steps taken for data cleaning. Additionally, you can explore the visualizations generated from the cleaned data using PowerBI.

## Original Dataset

The data used in this project was obtained from the Medical Expenditure Panel Survey (MEPS). You can access the original dataset using the following link:
[MEPS HC-228 Dataset](https://meps.ahrq.gov/mepsweb/data_stats/download_data_files_detail.jsp?cboPufNumber=HC-228)

## Codebook

For recoding values and understanding variable/column names, we referred to the following codebook:
[MEPS HC-228 Codebook](https://meps.ahrq.gov/mepsweb/data_stats/download_data_files_codebook.jsp?PUFId=H228)

## Data Cleaning

The data cleaning process involved both R and Excel to ensure the data was properly prepared for analysis. The following are the major steps taken during the Excel cleaning:

1. **Find and Replace Operations:**
   - Cleaned specific columns and data codes/values within the rows.

2. **Column Renaming and Value Recoding:**
   - Modified column names and recoded values for increased readability and usability.
   - Changed numeric codes into corresponding text values to make the data easier to interpret.

3. **Adding New Columns from Original Dataset:**
   - We added additional variables of interest from the original FULL dataset into the final cleaned table. These new columns were renamed accordingly.

4. **Data Merge:**
   - We matched the DUID's (DUPERSID) from the cleaned_final_table to the new_columns_added_jul_17 sheet (filtered by diabetes only) and merged the new columns from table 2 (new_columns_added_jul_17) into table 1 (cleaned_new_table).

## PowerBI Dashboard

To visualize the cleaned and organized data, we have created an interactive dashboard using PowerBI. Below is the link for the PowerBI dashboard: [https://app.powerbi.com/reportEmbed?reportId=5f78db27-a174-4951-94ed-025c2e8bf1b2]

The excel file with the final cleaned table can be found [here:](https://github.com/stremyjo/Diabetes-Exploratory-Data-Analysis-Dashboard/files/12141152/diabetes_eda_final_table-2.xlsx)


The PowerPoint file with the PowerBI dashboard can be found [here:](https://github.com/stremyjo/Diabetes-Exploratory-Data-Analysis-Dashboard/files/12141144/Diabetes.Exploratory.Data.Analysis.Dashboard.pptx)

A PDF version of the summarized findings can be found [here:](https://github.com/stremyjo/Diabetes-Exploratory-Data-Analysis-Dashboard/files/12141159/Diabetes.Exploratory.Data.Analysis.Dashboard.pdf)

Feel free to explore the dashboard and interact with the visualizations to gain insights from the data.

Thank you for visiting our Diabetes Exploratory Data Analysis Project repository! If you have any questions or feedback, please don't hesitate to reach out.
