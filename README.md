# Fablix: Movie Database Web App

## Built by: Thien Toan Vu & Senghoung Lim  
**Duration:** September 2023 to December 2023  

### Overview

Fablix is a robust movie database web application developed and deployed by Thien Toan Vu and Senghoung Lim. The project involved setting up AWS infrastructure, MySQL databases, and Tomcat servers. The implementation covers various aspects, including ETL pipelines, secure user authentication, and optimization strategies for improved performance.

### Features

- **AWS Infrastructure:** Architected and deployed Fablix on AWS, ensuring scalability and reliability.

- **ETL Pipelines:** Implemented Extract, Transform, Load (ETL) pipelines for parsing large XML files, facilitating efficient data handling.

- **Secure User Authentication:** Ensured secure user login with SHA256 hashing and session management.

- **Full-Text Search:** Incorporated a powerful full-text search feature to enhance user experience.

- **Auto-Complete with Cache:** Implemented auto-complete functionality with caching for improved response times.

- **Bot Detection:** Integrated reCAPTCHA for bot detection, enhancing website security.

- **SQL Injection Protection:** Implemented security measures, such as PreparedStatements, to protect against SQL injection attacks.

- **Performance Optimization:** Achieved a 50% boost in website performance through MySQL connection pooling, replication, and Apache load balancing.

### Project Structure

#### WebContent
- Contains all CSS, HTML, and JS files for the front end of the website.

#### src
- Contains backend servlets Java files. Some of them are ImprovedInsertion.java for parsing XML files, UpdateSecurePassword.java for password modification and encryption, and log_processing.java for calculating execution time, etc.

#### Stanford-Movies-XMLs
- Contains all XML files and .dtd files detailing elements in the XML files.

#### SQL
- **README.md:** Instructions on setting up the database.
- **create_table.sql:** Script for creating tables and their relations.
- **movie-data.sql:** Script for populating the tables.

#### Android 
- Contains files for running the Android simulation for Fablix.
