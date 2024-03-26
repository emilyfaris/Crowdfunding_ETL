# Crowdfunding_ETL

Completed by Aayushi Daliparthi and Emily Faris

This project focuses on extracting, transforming, and loading data related to crowdfunding campaigns from an Excel file into structured CSV files and then into a PostgreSQL database. The data encompasses categories, subcategories, campaign details, and contact information.

## Project Structure

The project is divided into several key sections:

1. **Data Extraction and Transformation**:
   - Creation of Category and Subcategory DataFrames (category.csv and subcategory.csv in the Resources folder).
   - Creation of the Campaign DataFrame (campaign.csv in the Resources folder).
   - Creation of the Contacts DataFrame (contacts.csv in the Resources folder).

2. **Database Creation**:
   - Sketching an Entity-Relationship Diagram (ERD) (crowdunding_ERD.png in the Resources folder).
   - Creating table schemas and a PostgreSQL database (crowfunding_db_schema.sql).
   - Importing CSV data into the database.

### Prerequisites

- Python 3.x
- pandas library
- PostgreSQL
- An environment to run SQL scripts (e.g., pgAdmin)

To install the required Python packages for this project, run in your terminal:
```
pip install -r requirements.txt
```
