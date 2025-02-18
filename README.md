# Talent_Analytics_Suite-

Overview
This project integrates KoboToolbox with Microsoft Excel to automate data collection and analysis for HR analytics. A form was created using KoboToolbox, and its data is dynamically linked to an Excel sheet using the KoboToolbox API. The processed data is then visualized in an interactive HR analytics dashboard.
Project Workflow
1. Creating the Form in KoboToolbox
•	The form was created using KoboToolbox.
•	It is accessible through the following link: Form.
•	The form includes fields for employee details such as name, age, year of joining, attrition status, and tenure.
•	Screenshot of the Form: (Attach a screenshot of the form here)
2. Integrating KoboToolbox Data with Excel
•	KoboToolbox API fetched real-time form responses into an Excel sheet.
•	API Link Used: KoboToolbox API
•	Steps to connect the form with Excel: 
1.	Open Excel and navigate to Data > Get Data > From Web.
2.	Paste the KoboToolbox API link and click Load.
3.	After submission of a new form, click Refresh All to update the data dynamically.
•	Dataset Link: [Dataset](https://github.com/Saher-Younas/Talent_Analytics_Suite-/blob/main/Talent_Analytics_Dataset.xlsx)
3. Data Processing in Excel
•	Additional columns were created in the Excel sheet to derive insights: 
o	Year of Joining: Extracted from the submitted date.
o	Attrition Status: Marked for employees who have left the company.
o	Tenure Calculation: Derived from the difference between the current year and the joining year.
o	Age Calculation: Based on the provided birth year.
4. Creating the Talent Analytics Dashboard
•	A background for the dashboard was designed in PowerPoint and saved as a JPEG image.
•	This background was imported into Excel, and different partitions were made for data visualization.
•	The dashboard sections were designed to reflect: 
o	Employee Demographics
o	Attrition Rate Analysis
o	Tenure Insights
o	Age Distribution
•	Dashboard Background Link:  

Screenshot of the Dashboard: 
 
5. Data Visualization and Analysis
•	Pivot Tables & Charts: 
o	A KPI sheet was created to perform various HR analyses.
o	Pivot tables were used to summarize key metrics.
o	Charts and graphs were added for enhanced visualization.
•	Interactive Features: 
o	Dynamic slicers were implemented to filter data interactively.
o	Real-time data updates ensure that the latest employee records are reflected in the dashboard.
6. Finalizing and Documentation
•	The complete project was tested to ensure real-time updates and accurate analysis.
•	This document serves as a guide to understanding the workflow, ensuring transparency and ease of use.
Summary
This Talent Analytics Suite effectively integrates KoboToolbox with Excel to automate HR data collection and visualization. The dashboard provides valuable insights into employee trends, attrition, and workforce demographics, making it a powerful tool for HR professionals.

