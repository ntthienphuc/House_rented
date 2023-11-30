
# SQL Project: Real-time Body Measurement Analysis

## Project Overview
This SQL project is part of the 'Real-time Body Measurement using Pose Estimation and Deep Learning' system. It involves creating and managing a database for storing and processing data related to user measurements, housing types, room rentals, and reviews.

## Database Structure
- **NGUOIDUNG**: Table for storing user information.
- **LOAINHA**: Table for different types of housing.
- **NHATRO**: Table for rental properties.
- **DANHGIA**: Table for storing reviews of the properties.

## Key Features
- Creation of a comprehensive database to manage real-time body measurements.
- Stored procedures for inserting, updating, and querying data efficiently.
- Functions for searching and aggregating data.
- Views to represent complex queries for easier access.
- Utilization of transactions to ensure data integrity.

## Installation
1. Ensure SQL Server or a compatible DBMS is installed.
2. Execute the SQL script to create the database and its tables.
3. Use the provided stored procedures and functions as needed.

## Usage
- **Insert Data**: Use the provided stored procedures (`spInsertNGUOIDUNG`, `spInsertNHATRO`, `spInsertDANHGIA`) to insert data into the tables.
- **Query Data**: Use the `spSearchRentHouse` stored procedure to search for rental properties based on various criteria.
- **Aggregate Data**: Use the `fnCountLikeDislike` function to get likes/dislikes for each property.
- **View Top Properties**: Access the `TopNhaTro` view to see the top-rated properties.
- **Data Removal**: Use `spDeleteGreatDislike` and `spDeleteDateInRange` to remove data based on specific conditions.

## Contributing
Contributions to this project are welcome. Please ensure you follow best practices for database management and SQL standards.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to the developers and contributors of the 'Real-time Body Measurement using Pose Estimation and Deep Learning' system.
