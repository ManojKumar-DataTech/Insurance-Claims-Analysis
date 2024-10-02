# Insurance-Claims-Analysis

Capstone Project: Insurance Claims Analysis
Objective :
-Database Schema creation for insurance data
-Populating database with sample insurance data
-Analyzing claims data for insights
-Creating index for better performance
-Setting up roles and permissions for database security

Task Description
1.	Database Schema creation
-	Define tables: Customers, Policies,Claims and Policytypes
-	Include fields such as CustomerID,PolicyID,ClaimID,PolicytypeID,ClaimAmount,PolicyStartDate,PolicyEndDate, etc.
2.	Data Population
3.	Analytic Queries
-Write query to calculate the total number of Claims per policy type
-Use analytical functions to determine the monthly claim frequency and average claim amount
4. Optimization
- Discuss the creation of indexes on any columns used frequently in where clauses or as join keys to improve performance
5. Roles and permissions
- Create Roles: ClaimsAnalyst and ClaimsManager
-“ClaimsAnalyst” role should have read-only access to claims and policies data.
-“ClaimsManager” role should have full access to claims data and the ability to update policy information.
