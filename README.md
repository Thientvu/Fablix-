# Fablix: Movie Database Web App
Built by: Thien Toan Vu & Senghoung Lim  
From: September 2023 to December 2023  
- Architected and deployed Fablix by setting up AWS infrastructure, MySQL databases, and Tomcat servers.
Implemented ETL pipelines for parsing large XML files, ensured secure login with SHA256 hashing and sessions, and incorporated features like full-text search, auto-complete with cache, bot detection using reCAPTCHA, and protection against SQL injection attacks via PreparedStatements, etc.
- Achieved a 50% boost in website performance through strategic optimizations like MySQL connection pooling, replication, and Apache load balancing, emphasizing a data-driven approach to problem-solving and system optimization.
## WebContent
- Contains all the CSS, HTML, JS files for the front end of the website

## src
- Contains all the backend servlets Java files
- Has ImprovedInsertion.java that is used to parse XML files
- Includes UpdateSecurePassword.java that is used to modify all the passwords and encrypt them
- Comprises log_processing.java that is used to calculate the execution time of the FulltextSearch servlet

## Stanford-Movies-XMLs
- Has all the XMLs files and .dtd files detailing all the elements in the xml files

## SQL
- README.md has all the instructions on how to set up the db
- create_table.sql is called to create all the tables and their relations
- movie-data.sql is used to populate the tables

## Android 
- Contains all the files to run the Android simulation for Fablix 