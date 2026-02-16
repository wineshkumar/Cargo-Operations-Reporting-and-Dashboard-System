# Cargo Operations Dashboard & Reporting System

## Overview
This project automates cargo performance reporting by directly integrating
Snowflake (centralized data warehouse) with Power BI, eliminating the need
for manual data extraction and report preparation.

The solution delivers interactive dashboards and automated reports for
import and export cargo operations, including SLA compliance and performance tracking.

## Business Problem
Previously, bulk data was extracted manually from 1Cargo and uploaded
into reporting tools to generate reports. This process was:

- Time-consuming
- Prone to human error
- Inefficient for large data volumes
- Limited in scalability

## Solution
A direct connection between Snowflake and Power BI was established,
enabling automated report generation and real-time dashboard updates.

The system supports:
- Scheduled reporting (daily, monthly, annual)
- Ad-hoc reporting capabilities
- Interactive dashboards with drill-down analysis
- Role-based access control

## Key Features
- Import Cargo Performance Dashboard
- Export Cargo Performance Dashboard
- SLA Performance Tracker with trend analysis
- Consolidated Import/Export Overview
- Filterable views (location, airline, cargo type, time period)
- Export to Excel, PDF, CSV
- Automated refresh scheduling

## Technology Stack
- Snowflake (Central Data Warehouse)
- Power BI (Reporting & Visualization)
- Power BI Service (Scheduling & Sharing)

## Business Impact
- Eliminated manual report preparation
- Improved decision-making visibility
- Reduced reporting turnaround time
- Enhanced data consistency and governance
- Scalable architecture for future growth
