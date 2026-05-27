# Enterprise O&M Dashboard

## Overview
Operational analytics dashboard designed to monitor work order completion rates, closure trends, and KPI performance across enterprise facilities operations.

## Technologies
- Power BI
- DAX
- Power Query
- SQL

## Features
- KPI scorecards
- Trend analysis
- Interactive filtering
- Drill-through reporting

## Data Model
![Executive Overview](screenshots/O&M_Model.png)

This dashboard was designed using a star schema approach, with centralized operational fact tables connected to supporting dimension tables such as facilities, work requests, equipment, rooms, etc. This structure improved dashboard scalability, simplified DAX calculations, and enabled more efficient KPI and trend analysis across enterprise reporting datasets.

This model was developed using Source of Truth exports from our internal database. The model seeks to replicate the Oracle database's relational qualities to enable model development given security restrictions. 

## Executive Overview Page

![Executive Overview](screenshots/O&M_PM_Overview.png)

This page provides leadership visibility into:
- Completion rates
- Closure trends
- Operational KPIs
- Enterprise performance metrics
