# Factory-Downtime-and-Gender-Pay-Equality-Analysis
### Deloitte Data Analytics Virtual Experience (Forage) Project

## Project Overview
This project was completed as part of the Deloitte Data Analytics Virtual Experience Program on Forage.
The project focuses on analyzing operational and workforce data from Daikibo Industrials to generate insights that support business decision-making.
The analysis was divided into two tasks:
- Machine Downtime Analysis using Tableau
- Gender Pay Equality Analysis using Microsoft Excel
- The project demonstrates how data analytics can be applied to identify operational inefficiencies and potential workplace inequalities.

**NOTE**: The dataset used in this project is simulated and provided for educational purposes.

## Business Problem
Daikibo Industrials operates several manufacturing factories globally. The company collects telemetry data from machines across its facilities to monitor operational performance.
The organization also received internal complaints regarding potential gender pay inequality across job roles.
The goal of this project was to analyze these datasets and answer key business questions.

## Task 1 – Factory Machine Downtime Analysis
### Objective
Analyze telemetry data to determine:
- Which factory experienced the highest machine downtime.
- Which machine type contributed the most downtime in that factory.

### Dataset
Telemetry data was collected from four Daikibo factories:
- Meiyo Factory – Tokyo, Japan
- Seiko Factory – Osaka, Japan
- Berlin Factory – Germany
- Shenzhen Factory – China
Each factory operates nine different machine types.
Machines send a status message every 10 minutes, and the dataset covers May 2021.

### Data Preparation
The dataset was imported into Tableau.
A calculated field called Unhealthy was created to measure machine downtime.
Logic used:
- Each telemetry message represents 10 minutes
- If machine status = Unhealthy, assign 10 minutes of downtime
- If machine status = Healthy, assign 0 minutes
This allowed total downtime to be calculated across factories and machine types.

Data Visualization - Dashboard
Two visualizations were created:
1. Total DownTime per Factory: A bar chart comparing total downtime across factory locations.
2. Total DownTime per Device Type: A bar chart showing downtime by machine type.
Both visualizations were combined into an interactive dashboard, where selecting a factory filters the machine-level breakdown.

![My Full Dashboard](My Full Dashboard.png)

📊 View the Interactive Tableau Dashboard:
👉 [https://public.tableau.com/app/profile/olorunfemi.modupe.peace/viz/DaikiboDowntimeDashboard/-DaikiboDowntimeDashboard-?publish=yes]



















