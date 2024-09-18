# TEC Job Placement System - SQL Project

This repository contains the SQL implementation and design of a dynamic job placement system for TEC, including a normalized database structure and advanced SQL queries for managing candidate qualifications, job openings, and placements.

## Project Overview
The primary objective of this project is to create a robust job placement system database using SQL. The database design follows a comprehensive approach, ensuring that entities such as candidates, qualifications, companies, and job openings are properly modeled and normalized. The key features of this system include:

- **Database Design**: Crow’s Foot Entity-Relationship Diagrams (ERD) to represent relationships between entities.
- **Normalization**: Implementation of First Normal Form (1NF), Second Normal Form (2NF), Third Normal Form (3NF), and Boyce-Codd Normal Form (BCNF) to ensure data integrity and eliminate redundancy.
- **Advanced SQL**: Use of complex SQL queries to categorize qualifications, generate consolidated reports, and analyze candidate qualifications distribution.

## Key Sections:
1. **Crow’s Foot ERDs (Before and After Normalization)**  
   Visual representation of the entities, relationships, and connectivity before and after the normalization process.
   
2. **Normalization Process**  
   - 1NF: Ensuring atomic values and removing repeating groups.
   - 2NF: Eliminating partial dependencies in tables with composite keys.
   - 3NF: Removing transitive dependencies and ensuring attributes depend only on the primary key.
   - BCNF: Strengthening 3NF by ensuring that all determinants are candidate keys.

3. **SQL Queries**  
   - **Qualification Categorization by Expertise**: Assigns expertise levels (Beginner, Intermediate, Expert) based on qualification names.
   - **Consolidated Company and Candidate List**: Combines and lists all companies and candidates, ensuring uniqueness.
   - **Qualification Distribution Analysis**: Counts the number of candidates per qualification, offering insights into the most prevalent qualifications.

## Technologies and Tools:
- **MySQL Workbench**: Used for designing the ERD diagrams and managing the database schema.
- **SQL**: Used for creating tables, relationships, and advanced data retrieval queries.

## How to Use:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tec-job-placement-system-sql.git

ERD and Normalization
The project includes ERD diagrams created before and after the normalization process, showcasing the relationships between entities such as candidates, job history, qualifications, and job openings.

Advanced SQL Queries:
Categorizing Qualifications: Classifies qualifications based on expertise levels using conditional logic.
Consolidated List of Companies and Candidates: Combines the names of all registered entities using a UNION query.
Qualification Distribution Analysis: Uses LEFT JOINs to count and display the number of candidates for each qualification.
