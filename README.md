# Comprehensive Database System

## Project Summary

This project involves the design and implementation of a comprehensive database system to streamline and optimize the operations of an organization dealing with precious metals. The database system is designed to manage customer information, orders, transactions, agent relationships, distributor details, and metal-related data. It ensures data integrity, security, and efficient retrieval. The database schema includes tables for web activity, orders, enums, order status, payment status, customers, transactions, wallets, agents, distributors, metals, and metal rates.

## Database Entity Details

| Database Entity Type (Table Name) | #Attribute Types (#Columns) | #Entities (#Rows) |
|-----------------------------------|-----------------------------|-------------------|
| preciousmetals_agents             | 8                           | 15                |
| preciousmetals_customers          | 11                          | 75                |
| preciousmetals_distributors       | 7                           | 20                |
| preciousmetals_enums              | 5                           | 9                 |
| preciousmetals_metalrates         | 4                           | 60                |
| preciousmetals_metals             | 2                           | 2                 |
| preciousmetals_orders             | 12                          | 261               |
| preciousmetals_orderstatus        | 2                           | 5                 |
| preciousmetals_paymentstatus      | 2                           | 4                 |
| preciousmetals_transactions       | 6                           | 261               |
| preciousmetals_wallets            | 6                           | 61                |
| preciousmetals_webactivity        | 7                           | 1000              |

## Key Features

- **Centralized Management**: Consolidates precious metals data, eliminating silos.
- **Data Accuracy**: Improved validation mechanisms enhance data accuracy and consistency.
- **Scalability**: Designed to adapt to the evolving demands of the precious metals market.
- **Efficiency**: Streamlines processes related to transactions, order processing, and customer interactions.

## Implementation

The database was implemented using MySQL for relational data management and MongoDB for NoSQL data replication. Python was used to connect to the database, perform data manipulation, and create visualizations for data analysis.

## Queries

The project includes various SQL queries to demonstrate the database's capabilities in handling complex queries and managing mid-scale datasets. Examples include fetching top successful orders, finding customers based on spending, and aggregating data by various metrics.

## Visualization

Data visualization was done using Python libraries such as Matplotlib and Seaborn to provide insights into the data stored in the database.

## Recommendations

1. **Cost-Benefit Analysis**: Periodically evaluate the relevance and effectiveness of the database system.
2. **Feedback Mechanism**: Establish a feedback loop with stakeholders to continuously improve and refine the database.

---

This repository contains all the code, data, and documentation needed to understand and replicate the project.
