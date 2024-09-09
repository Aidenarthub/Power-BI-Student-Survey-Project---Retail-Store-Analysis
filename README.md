# Power BI Student Survey Project - Retail Store Analysis
Project Overview
This project focuses on analyzing the spending habits of students across various retail stores in the United States. The dataset used is from a student survey which includes information about different types of purchases such as Video games, Indoor games, Toys, Books, and Gadgets. The main objective of the project is to extract meaningful insights using Power BI and create interactive visualizations.

Industry Type
Retail Store

Dataset
Student Survey

The dataset includes columns such as:

Store location
Store setting
Total Amount of Purchase (TAP)
Age groups
Various product categories (Video games, Outdoor sports, Indoor sports, etc.)
Problem Statement
The goal of this project is to create a Power BI report that provides insights into how much students are spending on different kinds of purchases across retail stores in various locations.

Key Objectives:
Tabular Visualization: Format the Total Amount of Purchase (TAP) based on ‘Store location’ and ‘Store setting’:

If TAP is between 0 and 35,000, records should be shown in Red.
If TAP is between 35,000 and 60,000, records should be shown in Yellow.
If TAP is above 60,000, records should be shown in Blue.
Matrix Visualization: Display the amount spent on Outdoor sports across different ages and store settings, using color formatting.

Funnel Chart: Visualize the Total Amount of Purchase by store setting with data labels as a percentage of the first.

Pie Chart: Show the Total Amount of Purchase by store location for Suburban store setting only (filtered context).

Scatter Plot:

Video games purchase vs Outdoor sports spend across age groups.
SandDance Plot: Indoor sports vs Video games spend across age groups.
Data Access Restriction: Implement row-level security to restrict data access for specific users (e.g., Mani only sees Rural data).

Master Dashboard & Refresh: Publish the report on the Power BI cloud service and schedule a refresh every 4 hours (6 times a day).

Power BI Q&A:

Show average age of students.

Create a Donut chart for the total amount of purchases by store location.

Power BI Features Used

Conditional Formatting in tabular visualization

Matrix Visualization with custom formatting

Funnel Chart, Pie Chart, and Scatter Plot for visual data representation

SandDance Plot for 3D interactive visualizations

Row-Level Security (RLS) to manage user access to specific data

Scheduled Data Refresh in Power BI cloud service

Q&A Feature to query data using natural language processing

Tools & Technologies

Power BI Desktop

Power BI Cloud Service

Power BI Q&A

Row-Level Security (RLS)
