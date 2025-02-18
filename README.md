# Talent Analytics Suite

## Overview
This project integrates **KoboToolbox** with **Microsoft Excel** to automate data collection and analysis for HR analytics. A form was created using KoboToolbox, and its data is dynamically linked to an Excel sheet using the **KoboToolbox API**. The processed data is then visualized in an **interactive HR analytics dashboard**.

## Project Workflow

### 1. Creating the Form in KoboToolbox
- The form was created using **KoboToolbox**.
- It is accessible through the following link: [KoboToolbox Form](https://ee.kobotoolbox.org/x/mja2VvRg).
- The form includes fields for employee details such as:
  - Name
  - Age
  - Year of Joining
  - Attrition Status
  - Tenure

### 2. Integrating KoboToolbox Data with Excel
- **KoboToolbox API** fetched real-time form responses into an Excel sheet.
- API Link Used: [KoboToolbox API](https://kf.kobotoolbox.org/api/v2/assets/)
- Steps to connect the form with Excel:
  1. Open **Excel** and navigate to **Data** > **Get Data** > **From Web**.
  2. Paste the KoboToolbox API link and click **Load**.
  3. After submission of a new form, click **Refresh All** to update the data dynamically.
- Dataset Link: *(https://github.com/Saher-Younas/Talent_Analytics_Suite-/blob/main/Talent_Analytics_Dataset.xlsx)*
- Screenshot of the Excel Integration: *![image](https://github.com/user-attachments/assets/8a844e4a-0118-461d-81e3-67d224034a06)
)*

### 3. Data Processing in Excel
- Additional columns were created in the Excel sheet to derive insights:
  - **Year of Joining**: Extracted from the submitted date.
  - **Attrition Status**: Marked for employees who have left the company.
  - **Tenure Calculation**: Derived from the difference between the current year and the joining year.
  - **Age Calculation**: Based on the provided birth year.


### 4. Creating the Talent Analytics Dashboard
- A **background for the dashboard** was designed in **PowerPoint** and saved as a **JPEG image**.
- This background was imported into Excel, and different partitions were made for **data visualization**.
- The dashboard sections were designed to reflect:
  - Employee Demographics
  - Attrition Rate Analysis
  - Tenure Insights
  - Age Distribution
- Dashboard Background Link: *![HR_Analytics_Dashboard_Background](https://github.com/user-attachments/assets/f60c58e1-1bdd-4f90-8088-9f975f547757)
*
- Screenshot of the Dashboard: *![image](https://github.com/user-attachments/assets/7f572665-0e2e-4432-9d5a-cde81b855058)
*
### 5. Data Visualization and Analysis
- **Pivot Tables & Charts**:
  - A **KPI sheet** was created to perform various HR analyses.
  - **Pivot tables** were used to summarize key metrics.
  - **Charts and graphs** were added for enhanced visualization.
- **Interactive Features**:
  - **Dynamic slicers** were implemented to filter data interactively.
  - **Real-time data updates** ensure that the latest employee records are reflected in the dashboard.

### 6. Finalizing and Documentation
- The complete project was **tested** to ensure **real-time updates** and **accurate analysis**.
- This document serves as a **guide** to understanding the workflow, ensuring transparency and ease of use.

## Summary
The **Talent Analytics Suite** effectively integrates **KoboToolbox** with **Excel** to automate **HR data collection and visualization**. The dashboard provides **valuable insights** into:
- Employee trends  
- Attrition rates  
- Workforce demographics  

This makes it a **powerful tool** for HR professionals.

