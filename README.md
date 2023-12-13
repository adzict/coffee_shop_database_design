# Designing a Relational Database

## Project Goal

Streamline operations and enhance data infrastructure for a national expansion of a New York-based coffee shop chain by designing a centralized relational database system. The objective is to improve operational efficiencies, consolidate data from various sources (accounting software, suppliers’ databases, POS systems, and spreadsheets), create and load database objects, and facilitate data-driven decision-making for executives. Additionally, subsets of required data will be exported and loaded into staging databases using different RDBMS to meet specific business partner needs.


## Data Information

Here are the data sources:

- Staff information held in a spreadsheet at HQ
- Sales outlet information held in a spreadsheet at HQ
- Sales data output as a CSV file from the POS system in the sales outlets
- Customer data output as a CSV file from a bespoke customer relationship management system
- Product information maintained in a spreadsheet exported from your supplier’s database

## Project Steps

This projects is divided into a series of tasks:

- Identify entities.
- Identity attributes.
- Create an entity relationship diagram (ERD) using the pgAdmin ERD Tool.
- Normalize tables.
- Define keys and relationships.
- Create database objects by generating and running the SQL script from the ERD Tool.
- Create a view and export the data.
- Create a materialized view and export the data.
- Import data into Datasette.
- Import data into a MySQL database.

