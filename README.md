# ID/x Partners Data Warehouse Repository

This repository contains SQL scripts used for data warehousing, reporting, and data analysis purposes.

## Overview

This repository supports the structured management of SQL queries and scripts for data processing and the consumption layer.

## Problem Statement

This project focuses on integrating and processing transaction data to produce information that is consistent, accurate, and timely.

The main scope of the project includes:

- integration of transaction data from multiple sources
- automated monitoring of active customer balances
- comprehensive processing of transaction history
- preparation of daily transaction summaries by count and value

## Data Warehouse Architecture

The data warehouse architecture in this repository consists of the following main layers:

- **Source**
- **ETL**
- **Data Warehouse**
- **Consumption Layer**

## Repository Structure

- **Balance Per Customer**  
  Contains scripts for balance-per-customer reporting.

- **DDL**  
  Folder for DDL scripts.

- **DML**  
  Folder for DML scripts.

- **Daily Transaction**  
  Contains scripts for daily transaction reporting.

## Data Warehouse Objects

The main objects in the data warehouse include:

- `DimBranch`
- `DimAccount`
- `DimCustomer`
- `FactTransaction`

## Consumption Layer

The consumption layer is used to support reporting and analysis, including:

- `SP Balance PerCustomer`
- `SP Daily Transaction`

## Repository Purpose

This repository is created to:

- store SQL scripts in a structured manner
- simplify query management
- support reporting requirements
- support data warehouse development
