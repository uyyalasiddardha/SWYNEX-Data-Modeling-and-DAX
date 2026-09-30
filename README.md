# SWYNEX Data Modeling and DAX

## Overview
This project was completed as part of the SWYNEX Power BI Internship.

The objective was to build a Power BI data model, create relationships between tables, and develop DAX measures for analysis.

## Dataset
The project uses a healthcare dataset containing patient and hospital-related information.

Key fields include:
- Patient ID
- Admission Date
- Discharge Date
- Age
- Gender
- Department
- Billing Amount
- Medical Condition
- Hospital
- Test Results

## Data Modeling
A dimension table, `DimDepartment`, was created from the Department field.

Relationship:
- `DimDepartment[Department]` → `Sheet1[Department]`
- Cardinality: One-to-Many
- Cross-filter direction: Single

## DAX Measures
The following measures were created:

- Total Patients
- Total Billing
- Average Age
- Average Billing

## Tools Used
- Microsoft Power BI
- Power Query
- DAX

##
