# Data-Warehousing-and-Visualisation

The data source (Sakila) used for building the warehouse was gotten from https://relational.fit.cvut.cz/dataset/Sakila

*A Dimensional model was created for the Data warehouse.
*Five dimensional tables and one fact table were created for the Data warehouse.
*SQL code for ETL (Extract, Transform, Load) was used to populate the Data warehouse from the Sakila database. Data was Extracted from Sakila database, Transformed to a format we want, then Loaded into the Data warehouse.
*Reports were developed from the Data warehouse.
*A dashboard in Tableau having four multi-diimensional visualistion was developed from the Data warehouse also.

Firstly, the database was created using: 
```
CREATE DATABASE filmRentalWareHouse
GO
USE filmRentalWarehouse
GO
```