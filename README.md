# File-Handler-Using-Python
# E-Commerce Product Information Management System

## Introduction

This project automates the management of e-commerce product information using Python. It focuses on CRUD operations (Create, Read, Update, Delete) for efficient data handling, improving data consistency and reducing manual entry errors. This system enables quick updates and retrieval of product details, sales data, and descriptions, making it essential for scalable e-commerce solutions.

## Features

- **CRUD Operations**: 
  - **Create**: Adds new product information, including sales data, product details, and descriptions.
  - **Read**: Retrieves and displays product information for easy review.
  - **Update**: Modifies existing product details and updates information as needed.
  - **Delete**: Removes all information related to discontinued products.

## Project Structure

- **Data Files**: Stored in the `main_folder` directory:
  - `sales_data.csv`: Contains sales data over 14 days for each product.
  - `product_details` folder: JSON files with detailed product information.
  - `product_description` folder: TXT files with product descriptions.
  
## Getting Started

1. **Clone the Repository**:
  

2. **Setup**:
    - Ensure Python 3.x is installed.
    - Install necessary packages:
        ```bash
        pip install -r requirements.txt
        ```

3. **File Structure**:
    - Place data files in the correct folders:
      ```
      main_folder/
      ├── sales_data.csv
      ├── product_details/
      └── product_description/
      ```

## Usage

1. **Load Data**: 
    - Run `load_data()` to load data from CSV, JSON, and TXT files.

2. **CRUD Operations**:
    - **Create**: Use `create()` to add product details, sales data, and descriptions.
    - **Read**: Use `read()` to view a product’s sales data, details, and descriptions.
    - **Update**: Use `update()` to modify product information.
    - **Delete**: Use `delete()` to remove all data for a product.

## Example Functions

```python
# Loading data
load_data()

# Creating a new product entry
create()

# Reading product information
read()

# Updating product information
update()

# Deleting a product entry
delete()


Data Files
sales_data.csv: Tracks daily sales data for each product over a two-week period (columns: Day1 to Day14).
product_details folder: Contains JSON files named by SKU (e.g., details_AISJDKFJW93NJ.json) with product specifications, price, and availability.
product_description folder: Contains TXT files named by SKU (e.g., description_AISJDKFJW93NJ.txt) with descriptive text about each product.
Problem Statement
In the dynamic landscape of e-commerce, efficiently managing product information is essential. Without a robust system, inconsistencies and inefficiencies can arise, impacting business operations. This project tackles these challenges by automating the addition, retrieval, updating, and deletion of product details, sales data, and product descriptions.

Solution Design
This project uses Python to develop a system that automates CRUD operations for e-commerce data management.

Functionality
Create: Use the create() function to add product data in three main categories:

add_sales_data(): Adds sales data.
add_product_details(): Adds product specifications and availability.
add_product_descriptions(): Adds a descriptive text for the product.
Read: Use the read() function to retrieve and display product data using:

display_sales_data(): Displays sales statistics.
display_product_details(): Shows product specifications.
display_product_descriptions(): Fetches product descriptions.
Update: The update() function modifies existing product data via:

update_sales_data(): Updates sales data.
update_product_details(): Modifies product specifications.
update_product_descriptions(): Updates product description text.
Delete: The delete() function removes all data related to a discontinued product SKU.

Master CRUD Function
The crud() function acts as a central hub for managing all CRUD operations, enabling seamless integration of data management tasks.


