# Designing-Implementing-a-Database-System-for-a-Music-Festival

As part of my Database Systems coursework, I developed a fully functional database system for the Blastonbury Pop Festival, handling artist management, security clearance, and performance scheduling using Oracle SQL, MySQL, PHP, and Java. This project involved database modeling, SQL query development, data migration, and backend connectivity.

💡 Project Overview
✅ Entity-Relationship (ER) Modeling & Database Design

Designed a normalized relational database schema based on festival requirements.
Identified entities (Bands, Musicians, Agents, Stages, Performances, Security Clearance, etc.) and relationships.
Established primary and foreign keys to maintain referential integrity.
✅ SQL Implementation in ORACLE DB

Created tables with constraints (Primary Key, Foreign Key, Unique, NOT NULL).
Implemented data insertion scripts, populating tables with musicians, bands, job roles, and event schedules.
Developed SQL Views & Triggers, including:
AgentJobs View – Displaying job roles managed by each agent.
Audit Trigger – Tracking deletions in the Agent table via tblCountDelete.
✅ Data Migration from ORACLE to MySQL (WAMP Server)

Installed and configured WAMP server for MySQL deployment.
Migrated database schema, constraints, and records from Oracle to MySQL.
Verified data consistency using MySQL queries & script execution.
✅ Backend Development & Data Display

PHP Integration:
Connected MySQL database with PHP scripts to fetch and display AgentJobs View in a web-based dashboard.
Implemented database authentication & query execution.
Java (JDBC) Integration:
Used Java Database Connectivity (JDBC) to fetch and display records from the Agent table in the command-line interface.
Ensured smooth data retrieval & exception handling.
