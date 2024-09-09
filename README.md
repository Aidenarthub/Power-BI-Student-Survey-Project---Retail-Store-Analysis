
# Power BI Student Survey Project - Retail Store Analysis

## Project Overview
This project focuses on analyzing the **spending habits of students** across various retail stores in the United States. The dataset used is from a **student survey**, which includes information about different types of purchases such as **Video games, Indoor games, Toys, Books, and Gadgets**. The main objective is to extract meaningful insights using **Power BI** and create **interactive visualizations**.

## Industry Type
**Retail Store**

## Dataset
**Student Survey**

### The dataset includes key columns such as:
- **Store Location**
- **Store Setting**
- **Total Amount of Purchase (TAP)**
- **Age Groups**
- **Various Product Categories** (e.g., Video games, Outdoor sports, Indoor sports, etc.)

## Problem Statement
The goal of this project is to create a Power BI report that provides insights into how much students are spending on different types of purchases across retail stores in various locations.

### Key Objectives:
1. **Tabular Visualization**: Format the **Total Amount of Purchase (TAP)** based on ‘Store Location’ and ‘Store Setting’:
   - If **TAP is between 0 and 35,000**, records should be shown in **Red**.
   - If **TAP is between 35,000 and 60,000**, records should be shown in **Yellow**.
   - If **TAP is above 60,000**, records should be shown in **Blue**.

2. **Matrix Visualization**: Display the amount spent on **Outdoor sports** across different ages and store settings, using **color formatting**.

3. **Funnel Chart**: Visualize the **Total Amount of Purchase** by store setting with data labels showing the **percentage of the first**.

4. **Pie Chart**: Display the **Total Amount of Purchase** by store location for **Suburban store settings only** (filtered context).

5. **Scatter Plot**:
   - Plot **Video games purchases** vs **Outdoor sports spending** across age groups.
   - Create a **SandDance Plot** for **Indoor sports vs Video games spending** across age groups.

6. **Data Access Restriction**: Implement **Row-Level Security (RLS)** to restrict data access for specific users (e.g., Mani only views Rural data).

7. **Master Dashboard & Scheduled Refresh**: Publish the report on the **Power BI cloud service** and schedule a **data refresh every 4 hours** (6 times a day).

8. **Power BI Q&A**:
   - Show the **average age** of students.
   - Create a **Donut Chart** for the total amount of purchases by store location.

## Power BI Features Used
- **Conditional Formatting** in tabular visualization
- **Matrix Visualization** with custom formatting
- **Funnel Chart, Pie Chart, and Scatter Plot** for visual data representation
- **SandDance Plot** for 3D interactive visualizations
- **Row-Level Security (RLS)** to manage user access to specific data
- **Scheduled Data Refresh** in Power BI cloud service
- **Q&A Feature** to query data using **natural language processing**

## Tools & Technologies
- **Power BI Desktop**
- **Power BI Cloud Service**
- **Power BI Q&A**
- **Row-Level Security (RLS)**
